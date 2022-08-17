//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine.protos](../../index.md)/[VersionDefKt](../index.md)/[Dsl](index.md)

# Dsl

[androidJvm]\
public final class [Dsl](index.md)

## Types

| Name | Summary |
|---|---|
| [BadConsumersProxy](-bad-consumers-proxy/index.md) | [androidJvm]<br>public final class [BadConsumersProxy](-bad-consumers-proxy/index.md) extends DslProxy<br>An uninstantiable, behaviorless type to represent the field in generics. |
| [Companion](-companion/index.md) | [androidJvm]<br>public class [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [clearMinConsumer](clear-min-consumer.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearMinConsumer](clear-min-consumer.md)()<br><pre> Any consumer below this version is not allowed to consume this data. </pre> |
| [clearProducer](clear-producer.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[clearProducer](clear-producer.md)()<br><pre> The version of the code that produced this data. </pre> |
| [getMinConsumer](get-min-consumer.md) | [androidJvm]<br>final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[getMinConsumer](get-min-consumer.md)() |
| [getProducer](get-producer.md) | [androidJvm]<br>final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[getProducer](get-producer.md)() |
| [setMinConsumer](set-min-consumer.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setMinConsumer](set-min-consumer.md)([Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)minConsumer) |
| [setProducer](set-producer.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setProducer](set-producer.md)([Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)producer) |

## Properties

| Name | Summary |
|---|---|
| [badConsumers](index.md#-189105437%2FProperties%2F-89531115) | [androidJvm]<br>private final DslList&lt;[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html), [VersionDefKt.Dsl.BadConsumersProxy](-bad-consumers-proxy/index.md)&gt;[badConsumers](index.md#-189105437%2FProperties%2F-89531115)<br><pre> Specific consumer versions which are disallowed (e.g. due to bugs). </pre> |
| [minConsumer](index.md#1951583159%2FProperties%2F-89531115) | [androidJvm]<br>private [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[minConsumer](index.md#1951583159%2FProperties%2F-89531115)<br><pre> Any consumer below this version is not allowed to consume this data. </pre> |
| [producer](index.md#-1254807479%2FProperties%2F-89531115) | [androidJvm]<br>private [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[producer](index.md#-1254807479%2FProperties%2F-89531115)<br><pre> The version of the code that produced this data. </pre> |
