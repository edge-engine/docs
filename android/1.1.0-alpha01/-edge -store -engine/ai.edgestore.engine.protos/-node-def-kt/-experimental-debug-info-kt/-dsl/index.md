//[Edge Store Engine](../../../../../index.md)/[ai.edgestore.engine.protos](../../../index.md)/[NodeDefKt](../../index.md)/[ExperimentalDebugInfoKt](../index.md)/[Dsl](index.md)

# Dsl

[androidJvm]\
public final class [Dsl](index.md)

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>public class [Companion](-companion/index.md) |
| [OriginalFuncNamesProxy](-original-func-names-proxy/index.md) | [androidJvm]<br>public final class [OriginalFuncNamesProxy](-original-func-names-proxy/index.md) extends DslProxy<br>An uninstantiable, behaviorless type to represent the field in generics. |
| [OriginalNodeNamesProxy](-original-node-names-proxy/index.md) | [androidJvm]<br>public final class [OriginalNodeNamesProxy](-original-node-names-proxy/index.md) extends DslProxy<br>An uninstantiable, behaviorless type to represent the field in generics. |

## Properties

| Name | Summary |
|---|---|
| [originalFuncNames](index.md#840424850%2FProperties%2F-89531115) | [androidJvm]<br>private final DslList&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [NodeDefKt.ExperimentalDebugInfoKt.Dsl.OriginalFuncNamesProxy](-original-func-names-proxy/index.md)&gt;[originalFuncNames](index.md#840424850%2FProperties%2F-89531115)<br><pre> This is intended to store the list of names of the functions from the original graph that this node was derived. For example if this node, say C, was result of a fusion of node A in function FA and node B in function FB, then `original_funcs` would be {FA, FB}. If the node is in the top level graph, the `original_func` is empty. This information, with the `original_node_names` can be used to map errors originating at the current ndoe to some top level source code. </pre> |
| [originalNodeNames](index.md#-612272%2FProperties%2F-89531115) | [androidJvm]<br>private final DslList&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [NodeDefKt.ExperimentalDebugInfoKt.Dsl.OriginalNodeNamesProxy](-original-node-names-proxy/index.md)&gt;[originalNodeNames](index.md#-612272%2FProperties%2F-89531115)<br><pre> Opaque string inserted into error messages created by the runtime. This is intended to store the list of names of the nodes from the original graph that this node was derived. For example if this node, say C, was result of a fusion of 2 nodes A and B, then 'original_node' would be {A, B}. This information can be used to map errors originating at the current node to some top level source code. </pre> |
