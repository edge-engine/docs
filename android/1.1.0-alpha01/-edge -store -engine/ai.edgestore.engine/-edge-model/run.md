//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine](../index.md)/[EdgeModel](index.md)/[run](run.md)

# run

[androidJvm]\

abstract [Recognitions](../../ai.edgestore.engine.collections/-recognitions/index.md)[run](run.md)([List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[Object](https://developer.android.com/reference/kotlin/java/lang/Object.html)&gt;inputs)

Run inference on the edge models. Pack the input data in a list and pass it as argument. The input data depends on the type of model. If for example a vision based model then input data will be a bitmap image. So for that we will pass in listOf(bitmap).

#### Return

returns a [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html) of [Recognition](../../ai.edgestore.engine.collections/-recognition/index.md). The return value has further properties mentioned here: [Recognitions](../../ai.edgestore.engine.collections/-recognitions/index.md). Each recognition represents a single detection.

Example: Imagine that you have a problem where you need location of people's eyes so you use Centernet Keypoints Model. This model returns a [Recognition](../../ai.edgestore.engine.collections/-recognition/index.md) for each detected person. In each [Recognition](../../ai.edgestore.engine.collections/-recognition/index.md) you will find the confidence of detection (0-1) i.e. how sure you are that this is a person. Location of person in the image and finally the 17 body keypoints that include eyes of the person. If we have 2 people then we have two [Recognition](../../ai.edgestore.engine.collections/-recognition/index.md) objects in [Recognitions](../../ai.edgestore.engine.collections/-recognitions/index.md)

## Parameters

androidJvm

| | |
|---|---|
| inputs | [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of inputs accepted by the model. Currently [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html) images are supported as input. Number and order of inputs will depend on the model. |
