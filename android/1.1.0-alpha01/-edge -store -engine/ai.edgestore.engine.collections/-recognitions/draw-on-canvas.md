//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Recognitions](index.md)/[drawOnCanvas](draw-on-canvas.md)

# drawOnCanvas

[androidJvm]\

final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[drawOnCanvas](draw-on-canvas.md)([Canvas](https://developer.android.com/reference/kotlin/android/graphics/Canvas.html)canvas, [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)textSizePx, [Matrix](https://developer.android.com/reference/kotlin/android/graphics/Matrix.html)coordinatesMapMatrix)

Draws recognitions on canvas

## Parameters

androidJvm

| | |
|---|---|
| textSizePx | The size of text drawn to show name of detections if location is present. |
| coordinatesMapMatrix | A matrix to map x,y values in keypoints and locations to a new location. Useful if your canvas and input bitmap coordinates don't match.<br>To make textSizePx adjusted according to your device screen you can try:<br>textSizePx = TypedValue.applyDimension(<br>TypedValue.COMPLEX_UNIT_DIP,<br>18F,<br>context.resources.displayMetrics<br>) |
