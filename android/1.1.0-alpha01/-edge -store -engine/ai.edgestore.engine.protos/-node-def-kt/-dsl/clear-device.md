//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[NodeDefKt](../index.md)/[Dsl](index.md)/[clearDevice](clear-device.md)

# clearDevice

[androidJvm]\

final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearDevice](clear-device.md)()

<pre>
A (possibly partial) specification for the device on which this
node should be placed.
The expected syntax for this string is as follows:
DEVICE_SPEC ::= PARTIAL_SPEC
PARTIAL_SPEC ::= ("/" CONSTRAINT) *
CONSTRAINT ::= ("job:" JOB_NAME)
    | ("replica:" [1-9][0-9]*)
    | ("task:" [1-9][0-9]*)
    | ("device:" [A-Za-z]* ":" ([1-9][0-9]* | "*") )
Valid values for this string include:
* "/job:worker/replica:0/task:1/device:GPU:3"  (full specification)
* "/job:worker/device:GPU:3"                   (partial specification)
* ""                                    (no specification)
If the constraints do not resolve to a single device (or if this
field is empty or not present), the runtime will attempt to
choose a device automatically.
</pre>

<code>string device = 4;</code>
