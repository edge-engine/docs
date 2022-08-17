//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[AttrValueKt](../index.md)/[Dsl](index.md)

# Dsl

[androidJvm]\
public final class [Dsl](index.md)

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>public class [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [clearB](clear-b.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearB](clear-b.md)()<br><pre> "bool" </pre> |
| [clearF](clear-f.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearF](clear-f.md)()<br><pre> "float" </pre> |
| [clearFunc](clear-func.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearFunc](clear-func.md)()<br><pre> "func" represents a function. func.name is a function's name or a primitive op's name. func.attr.first is the name of an attr defined for that function. func.attr.second is the value for that attr in the instantiation. </pre> |
| [clearI](clear-i.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearI](clear-i.md)()<br><pre> "int" </pre> |
| [clearList](clear-list.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearList](clear-list.md)()<br><pre>     TensorShapeProto shape = 7;  // "shape"     TensorProto tensor = 8;      // "tensor" </pre> |
| [clearPlaceholder](clear-placeholder.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearPlaceholder](clear-placeholder.md)()<br><pre> This is a placeholder only used in nodes defined inside a function.  It indicates the attr value will be supplied when the function is instantiated.  For example, let us suppose a node "N" in function "FN". "N" has an attr "A" with value placeholder = "foo". When FN is instantiated with attr "foo" set to "bar", the instantiated node N's attr A will have been given the value "bar". </pre> |
| [clearS](clear-s.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearS](clear-s.md)()<br><pre> "string" </pre> |
| [clearType](clear-type.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearType](clear-type.md)()<br><pre> "type" </pre> |
| [clearValue](clear-value.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearValue](clear-value.md)() |
| [getB](get-b.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[getB](get-b.md)() |
| [getF](get-f.md) | [androidJvm]<br>final [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[getF](get-f.md)() |
| [getFunc](get-func.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getFunc](get-func.md)() |
| [getI](get-i.md) | [androidJvm]<br>final [Long](https://developer.android.com/reference/kotlin/java/lang/Long.html)[getI](get-i.md)() |
| [getList](get-list.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getList](get-list.md)() |
| [getPlaceholder](get-placeholder.md) | [androidJvm]<br>final [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[getPlaceholder](get-placeholder.md)() |
| [getS](get-s.md) | [androidJvm]<br>final ByteString[getS](get-s.md)() |
| [getType](get-type.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getType](get-type.md)() |
| [getValueCase](get-value-case.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getValueCase](get-value-case.md)() |
| [hasB](has-b.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasB](has-b.md)()<br><pre> "bool" </pre> |
| [hasF](has-f.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasF](has-f.md)()<br><pre> "float" </pre> |
| [hasFunc](has-func.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasFunc](has-func.md)()<br><pre> "func" represents a function. func.name is a function's name or a primitive op's name. func.attr.first is the name of an attr defined for that function. func.attr.second is the value for that attr in the instantiation. </pre> |
| [hasI](has-i.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasI](has-i.md)()<br><pre> "int" </pre> |
| [hasList](has-list.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasList](has-list.md)()<br><pre>     TensorShapeProto shape = 7;  // "shape"     TensorProto tensor = 8;      // "tensor" </pre> |
| [hasPlaceholder](has-placeholder.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasPlaceholder](has-placeholder.md)()<br><pre> This is a placeholder only used in nodes defined inside a function.  It indicates the attr value will be supplied when the function is instantiated.  For example, let us suppose a node "N" in function "FN". "N" has an attr "A" with value placeholder = "foo". When FN is instantiated with attr "foo" set to "bar", the instantiated node N's attr A will have been given the value "bar". </pre> |
| [hasS](has-s.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasS](has-s.md)()<br><pre> "string" </pre> |
| [hasType](has-type.md) | [androidJvm]<br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasType](has-type.md)()<br><pre> "type" </pre> |
| [setB](set-b.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setB](set-b.md)([Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)b) |
| [setF](set-f.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setF](set-f.md)([Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)f) |
| [setFunc](set-func.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setFunc](set-func.md)(&lt;ERROR CLASS&gt;func) |
| [setI](set-i.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setI](set-i.md)([Long](https://developer.android.com/reference/kotlin/java/lang/Long.html)i) |
| [setList](set-list.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setList](set-list.md)(&lt;ERROR CLASS&gt;list) |
| [setPlaceholder](set-placeholder.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setPlaceholder](set-placeholder.md)([String](https://developer.android.com/reference/kotlin/java/lang/String.html)placeholder) |
| [setS](set-s.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setS](set-s.md)(ByteStrings) |
| [setType](set-type.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setType](set-type.md)(&lt;ERROR CLASS&gt;type) |

## Properties

| Name | Summary |
|---|---|
| [b](index.md#-1771025990%2FProperties%2F-89531115) | [androidJvm]<br>private [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[b](index.md#-1771025990%2FProperties%2F-89531115)<br><pre> "bool" </pre> |
| [f](index.md#-1646946762%2FProperties%2F-89531115) | [androidJvm]<br>private [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[f](index.md#-1646946762%2FProperties%2F-89531115)<br><pre> "float" </pre> |
| [func](index.md#509356282%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[func](index.md#509356282%2FProperties%2F-89531115)<br><pre> "func" represents a function. func.name is a function's name or a primitive op's name. func.attr.first is the name of an attr defined for that function. func.attr.second is the value for that attr in the instantiation. </pre> |
| [i](index.md#-1553887341%2FProperties%2F-89531115) | [androidJvm]<br>private [Long](https://developer.android.com/reference/kotlin/java/lang/Long.html)[i](index.md#-1553887341%2FProperties%2F-89531115)<br><pre> "int" </pre> |
| [list](index.md#175309920%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[list](index.md#175309920%2FProperties%2F-89531115)<br><pre>     TensorShapeProto shape = 7;  // "shape"     TensorProto tensor = 8;      // "tensor" </pre> |
| [placeholder](index.md#1268682505%2FProperties%2F-89531115) | [androidJvm]<br>private [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[placeholder](index.md#1268682505%2FProperties%2F-89531115)<br><pre> This is a placeholder only used in nodes defined inside a function.  It indicates the attr value will be supplied when the function is instantiated.  For example, let us suppose a node "N" in function "FN". "N" has an attr "A" with value placeholder = "foo". When FN is instantiated with attr "foo" set to "bar", the instantiated node N's attr A will have been given the value "bar". </pre> |
| [s](index.md#-1243689271%2FProperties%2F-89531115) | [androidJvm]<br>private ByteString[s](index.md#-1243689271%2FProperties%2F-89531115)<br><pre> "string" </pre> |
| [type](index.md#-1705800380%2FProperties%2F-89531115) | [androidJvm]<br>private &lt;ERROR CLASS&gt;[type](index.md#-1705800380%2FProperties%2F-89531115)<br><pre> "type" </pre> |
| [valueCase](index.md#1727636411%2FProperties%2F-89531115) | [androidJvm]<br>private final &lt;ERROR CLASS&gt;[valueCase](index.md#1727636411%2FProperties%2F-89531115) |
