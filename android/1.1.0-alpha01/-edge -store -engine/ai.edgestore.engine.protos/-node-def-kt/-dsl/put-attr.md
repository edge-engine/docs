//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[NodeDefKt](../index.md)/[Dsl](index.md)/[putAttr](put-attr.md)

# putAttr

[androidJvm]\

final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[putAttr](put-attr.md)(DslMap&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), &lt;ERROR CLASS&gt;, [NodeDefKt.Dsl.AttrProxy](-attr-proxy/index.md)&gt;$self, [String](https://developer.android.com/reference/kotlin/java/lang/String.html)key, &lt;ERROR CLASS&gt;value)

<pre>
Operation-specific graph-construction-time configuration.
Note that this should include all attrs defined in the
corresponding OpDef, including those with a value matching
the default -- this allows the default to change and makes
NodeDefs easier to interpret on their own.  However, if
an attr with a default is not specified in this list, the
default will be used.
The "names" (keys) must match the regexp "[a-z][a-z0-9_]+" (and
one of the names from the corresponding OpDef's attr field).
The values must have a type matching the corresponding OpDef
attr's type field.
TODO(josh11b): Add some examples here showing best practices.
</pre>

<code>map<string, .GraphMetadata.AttrValue> attr = 5;</code>
