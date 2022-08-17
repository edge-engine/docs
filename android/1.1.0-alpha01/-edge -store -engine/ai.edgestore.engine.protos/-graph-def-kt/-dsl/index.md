//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[GraphDefKt](../index.md)/[Dsl](index.md)

# Dsl

[androidJvm]\
public final class [Dsl](index.md)

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>public class [Companion](-companion/index.md) |
| [NodeProxy](-node-proxy/index.md) | [androidJvm]<br>public final class [NodeProxy](-node-proxy/index.md) extends DslProxy<br>An uninstantiable, behaviorless type to represent the field in generics. |

## Functions

| Name | Summary |
|---|---|
| [clearDeviceOptions](clear-device-options.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearDeviceOptions](clear-device-options.md)()<br><code>.GraphMetadata.OptimalOptions deviceOptions = 6;</code> |
| [clearLabelMap](clear-label-map.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearLabelMap](clear-label-map.md)()<br><code>.GraphMetadata.StringIntLabelMap labelMap = 5;</code> |
| [clearVersion](clear-version.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearVersion](clear-version.md)()<br><pre> Deprecated single version field; use versions above instead.  Since all GraphDef changes before "versions" was introduced were forward compatible, this field is entirely ignored. </pre> |
| [clearVersions](clear-versions.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearVersions](clear-versions.md)()<br><pre> Compatibility versions of the graph.  See core/public/version.h for version history.  The GraphDef version is distinct from the TensorFlow version, and each release of TensorFlow will support a range of GraphDef versions. </pre> |
| [getDeviceOptions](get-device-options.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getDeviceOptions](get-device-options.md)() |
| [getLabelMap](get-label-map.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getLabelMap](get-label-map.md)() |
| [getVersion](get-version.md) | [androidJvm]<br>final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[getVersion](get-version.md)() |
| [getVersions](get-versions.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getVersions](get-versions.md)() |
| [hasDeviceOptions](has-device-options.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasDeviceOptions](has-device-options.md)()<br><code>.GraphMetadata.OptimalOptions deviceOptions = 6;</code> |
| [hasLabelMap](has-label-map.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasLabelMap](has-label-map.md)()<br><code>.GraphMetadata.StringIntLabelMap labelMap = 5;</code> |
| [hasVersions](has-versions.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasVersions](has-versions.md)()<br><pre> Compatibility versions of the graph.  See core/public/version.h for version history.  The GraphDef version is distinct from the TensorFlow version, and each release of TensorFlow will support a range of GraphDef versions. </pre> |
| [setDeviceOptions](set-device-options.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setDeviceOptions](set-device-options.md)(&lt;ERROR CLASS&gt;deviceOptions) |
| [setLabelMap](set-label-map.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setLabelMap](set-label-map.md)(&lt;ERROR CLASS&gt;labelMap) |
| [setVersion](set-version.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setVersion](set-version.md)(@[Deprecated](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-deprecated/index.html)(message = "Field version is deprecated")[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)version) |
| [setVersions](set-versions.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setVersions](set-versions.md)(&lt;ERROR CLASS&gt;versions) |

## Properties

| Name | Summary |
|---|---|
| [deviceOptions](index.md#416926381%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[deviceOptions](index.md#416926381%2FProperties%2F-89531115)<br><code>.GraphMetadata.OptimalOptions deviceOptions = 6;</code> |
| [labelMap](index.md#-1312518499%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[labelMap](index.md#-1312518499%2FProperties%2F-89531115)<br><code>.GraphMetadata.StringIntLabelMap labelMap = 5;</code> |
| [node](index.md#205005731%2FProperties%2F-89531115) | [androidJvm]<br>private final DslList&lt;&lt;ERROR CLASS&gt;, [GraphDefKt.Dsl.NodeProxy](-node-proxy/index.md)&gt;[node](index.md#205005731%2FProperties%2F-89531115)<br><code>repeated .GraphMetadata.NodeDef node = 1;</code> |
| [version](index.md#2098815293%2FProperties%2F-89531115) | [androidJvm]<br>@[Deprecated](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-deprecated/index.html)(message = "Field version is deprecated")<br>~~private~~ [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[~~version~~](index.md#2098815293%2FProperties%2F-89531115)<br><pre> Deprecated single version field; use versions above instead.  Since all GraphDef changes before "versions" was introduced were forward compatible, this field is entirely ignored. </pre> |
| [versions](index.md#-2089947862%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[versions](index.md#-2089947862%2FProperties%2F-89531115)<br><pre> Compatibility versions of the graph.  See core/public/version.h for version history.  The GraphDef version is distinct from the TensorFlow version, and each release of TensorFlow will support a range of GraphDef versions. </pre> |
