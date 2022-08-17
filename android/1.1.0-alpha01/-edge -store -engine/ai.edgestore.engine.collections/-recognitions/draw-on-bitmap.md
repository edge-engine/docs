//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Recognitions](index.md)/[drawOnBitmap](draw-on-bitmap.md)

# drawOnBitmap

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[drawOnBitmap](draw-on-bitmap.md)([Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)bitmapInput, [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)textSizePx)

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[drawOnBitmap](draw-on-bitmap.md)([Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)bitmapInput)

Draws recognitions on bitmap

#### Return

A bitmap with keypoints, locations, and segmentation masks drawn in.

## Parameters

androidJvm

| | |
|---|---|
| bitmapInput | The input bitmap. Remains unchanged. |
| textSizePx | The size of text drawn to show name of detections if location is present.<br>To make textSizePx adjusted according to your device screen you can try:<br>textSizePx = TypedValue.applyDimension(<br>TypedValue.COMPLEX_UNIT_DIP,<br>18F,<br>context.resources.displayMetrics<br>) |
