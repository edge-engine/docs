//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[AttrValueKt](../index.md)/[Dsl](index.md)/[clearPlaceholder](clear-placeholder.md)

# clearPlaceholder

[androidJvm]\

final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearPlaceholder](clear-placeholder.md)()

<pre>
This is a placeholder only used in nodes defined inside a
function.  It indicates the attr value will be supplied when
the function is instantiated.  For example, let us suppose a
node "N" in function "FN". "N" has an attr "A" with value
placeholder = "foo". When FN is instantiated with attr "foo"
set to "bar", the instantiated node N's attr A will have been
given the value "bar".
</pre>

<code>string placeholder = 9;</code>
