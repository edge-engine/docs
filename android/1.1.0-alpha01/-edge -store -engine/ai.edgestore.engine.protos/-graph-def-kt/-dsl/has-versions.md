//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[GraphDefKt](../index.md)/[Dsl](index.md)/[hasVersions](has-versions.md)

# hasVersions

[androidJvm]\

final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasVersions](has-versions.md)()

<pre>
Compatibility versions of the graph.  See core/public/version.h for version
history.  The GraphDef version is distinct from the TensorFlow version, and
each release of TensorFlow will support a range of GraphDef versions.
</pre>

<code>.GraphMetadata.VersionDef versions = 4;</code>

#### Return

Whether the versions field is set.
