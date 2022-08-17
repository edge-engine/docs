//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[SemanticSegmentationResults](index.md)

# SemanticSegmentationResults

[androidJvm]\
public final class [SemanticSegmentationResults](index.md)

A class containing segmentation mask, overlay functions, and helper utilities to process segmentation results from model inference (run function).

## Parameters

androidJvm

| | |
|---|---|
| segmentation | TFLite task api segmentation mask (bound to change) |
| inputImage | The image for which the segmentation mask was generated |

## Constructors

| | |
|---|---|
| [SemanticSegmentationResults](-semantic-segmentation-results.md) | [androidJvm]<br>[SemanticSegmentationResults](index.md)[SemanticSegmentationResults](-semantic-segmentation-results.md)(&lt;ERROR CLASS&gt;segmentation, [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)inputImage) |

## Functions

| Name | Summary |
|---|---|
| [drawOnCanvas](draw-on-canvas.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[drawOnCanvas](draw-on-canvas.md)([Canvas](https://developer.android.com/reference/kotlin/android/graphics/Canvas.html)canvas, [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)alpha) |
| [filteredInputImage](filtered-input-image.md) | [androidJvm]<br>final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[filteredInputImage](filtered-input-image.md)([String](https://developer.android.com/reference/kotlin/java/lang/String.html)label)<br>Extract the pixels of input image that correspond to the given [label](filtered-input-image.md) Rest of the image is transparent. |
| [getAlphaValue](get-alpha-value.md) | [androidJvm]<br>final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[getAlphaValue](get-alpha-value.md)()<br>Alpha channel value for overlaying mask on top on [inputImage](index.md#-326181739%2FProperties%2F-89531115) |
| [getFoundDetections](get-found-detections.md) | [androidJvm]<br>final [Set](https://developer.android.com/reference/kotlin/java/util/Set.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;[getFoundDetections](get-found-detections.md)() |
| [getFullColorLabelMap](get-full-color-label-map.md) | [androidJvm]<br>final &lt;ERROR CLASS&gt;[getFullColorLabelMap](get-full-color-label-map.md)()<br>map from label name to color |
| [getInputImage](get-input-image.md) | [androidJvm]<br>final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[getInputImage](get-input-image.md)() |
| [getMaskOverlayOnOriginal](get-mask-overlay-on-original.md) | [androidJvm]<br>final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[getMaskOverlayOnOriginal](get-mask-overlay-on-original.md)() |
| [getSegmentationLabel](get-segmentation-label.md) | [androidJvm]<br>final [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[MaskLabel](../-mask-label/index.md)&gt;[getSegmentationLabel](get-segmentation-label.md)() |
| [getSegmentationMask](get-segmentation-mask.md) | [androidJvm]<br>final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[getSegmentationMask](get-segmentation-mask.md)() |
| [maskOverlayOnOriginal](mask-overlay-on-original.md) | [androidJvm]<br>final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[maskOverlayOnOriginal](mask-overlay-on-original.md)([Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)overlayAlpha)<br>same as [maskOverlayOnOriginal](mask-overlay-on-original.md) but with optional alpha value parameter for the mask image |
| [setAlphaValue](set-alpha-value.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setAlphaValue](set-alpha-value.md)([Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)alphaValue)<br>Alpha channel value for overlaying mask on top on [inputImage](index.md#-326181739%2FProperties%2F-89531115) |

## Properties

| Name | Summary |
|---|---|
| [alphaValue](index.md#1480554451%2FProperties%2F-89531115) | [androidJvm]<br>private [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[alphaValue](index.md#1480554451%2FProperties%2F-89531115)<br>Alpha channel value for overlaying mask on top on [inputImage](index.md#-326181739%2FProperties%2F-89531115) |
| [foundDetections](index.md#535123012%2FProperties%2F-89531115) | [androidJvm]<br>private final [Set](https://developer.android.com/reference/kotlin/java/util/Set.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;[foundDetections](index.md#535123012%2FProperties%2F-89531115)<br>Names of labels found in the segmentation mask |
| [fullColorLabelMap](index.md#-156956744%2FProperties%2F-89531115) | [androidJvm]<br>private final &lt;ERROR CLASS&gt;[fullColorLabelMap](index.md#-156956744%2FProperties%2F-89531115)<br>map from label name to color |
| [inputImage](index.md#-326181739%2FProperties%2F-89531115) | [androidJvm]<br>private final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[inputImage](index.md#-326181739%2FProperties%2F-89531115) |
| [maskOverlayOnOriginal](index.md#-1731476608%2FProperties%2F-89531115) | [androidJvm]<br>private final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[maskOverlayOnOriginal](index.md#-1731476608%2FProperties%2F-89531115)<br>segmentation mask resized and overlayed on original image, all detections are shown |
| [segmentationLabel](index.md#1855406082%2FProperties%2F-89531115) | [androidJvm]<br>private final [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[MaskLabel](../-mask-label/index.md)&gt;[segmentationLabel](index.md#1855406082%2FProperties%2F-89531115) |
| [segmentationMask](index.md#-1599446408%2FProperties%2F-89531115) | [androidJvm]<br>private final [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)[segmentationMask](index.md#-1599446408%2FProperties%2F-89531115)<br>Segmentation of mask type [Bitmap.Config.ARGB_8888](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.Config.html#ARGB_8888) same size as [inputImage](index.md#-326181739%2FProperties%2F-89531115) lazily evaluated. The colors of mask are related to colorLabelMap |
