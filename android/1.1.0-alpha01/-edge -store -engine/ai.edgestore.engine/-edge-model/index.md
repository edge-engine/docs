//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine](../index.md)/[EdgeModel](index.md)

# EdgeModel

[androidJvm]\
public interface [EdgeModel](index.md)

A helper class to load and run Edge Store Models.

Following options are available to load models:

[EdgeModel.fromFile](-companion/from-file.md)

[EdgeModel.fromAsset](-companion/from-asset.md)

[EdgeModel.fromInputStream](-companion/from-input-stream.md)

Use [run](run.md) method to perform inference on the models.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>public class [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [androidJvm]<br>abstract [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[close](close.md)() |
| [getModelStats](get-model-stats.md) | [androidJvm]<br>abstract [ModelStats](../-model-stats/index.md)[getModelStats](get-model-stats.md)() |
| [resetStats](reset-stats.md) | [androidJvm]<br>abstract [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[resetStats](reset-stats.md)() |
| [run](run.md) | [androidJvm]<br>abstract [Recognitions](../../ai.edgestore.engine.collections/-recognitions/index.md)[run](run.md)([List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[Object](https://developer.android.com/reference/kotlin/java/lang/Object.html)&gt;inputs)<br>Run inference on the edge models. Pack the input data in a list and pass it as argument. The input data depends on the type of model. If for example a vision based model then input data will be a bitmap image. So for that we will pass in listOf(bitmap). |
| [setModelStats](set-model-stats.md) | [androidJvm]<br>abstract [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setModelStats](set-model-stats.md)([ModelStats](../-model-stats/index.md)modelStats) |
