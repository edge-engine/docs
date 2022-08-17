//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Keypoint](index.md)

# Keypoint

[androidJvm]\
public final class [Keypoint](index.md)

Keypoint represents a point of interest inside an image. It is represented by [x](index.md#-1254913491%2FProperties%2F-89531115),[y](index.md#-1223893684%2FProperties%2F-89531115) (pixel coordinates), [confidence](index.md#1776634251%2FProperties%2F-89531115) - confidence of keypoint, and [name](index.md#-1179405654%2FProperties%2F-89531115) of the keypoint.

An example would be

Keypoint(x:40,y:110.5,confidence:0.80,name:"Nose")

## Constructors

| | |
|---|---|
| [Keypoint](-keypoint.md) | [androidJvm]<br>[Keypoint](index.md)[Keypoint](-keypoint.md)([Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)x, [Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)y, [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)confidence, [String](https://developer.android.com/reference/kotlin/java/lang/String.html)name) |

## Functions

| Name | Summary |
|---|---|
| [getConfidence](get-confidence.md) | [androidJvm]<br>final [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[getConfidence](get-confidence.md)() |
| [getName](get-name.md) | [androidJvm]<br>final [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[getName](get-name.md)() |
| [getX](get-x.md) | [androidJvm]<br>final [Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)[getX](get-x.md)() |
| [getY](get-y.md) | [androidJvm]<br>final [Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)[getY](get-y.md)() |

## Properties

| Name | Summary |
|---|---|
| [confidence](index.md#1776634251%2FProperties%2F-89531115) | [androidJvm]<br>private final [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[confidence](index.md#1776634251%2FProperties%2F-89531115) |
| [name](index.md#-1179405654%2FProperties%2F-89531115) | [androidJvm]<br>private final [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[name](index.md#-1179405654%2FProperties%2F-89531115) |
| [x](index.md#-1254913491%2FProperties%2F-89531115) | [androidJvm]<br>private final [Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)[x](index.md#-1254913491%2FProperties%2F-89531115) |
| [y](index.md#-1223893684%2FProperties%2F-89531115) | [androidJvm]<br>private final [Number](https://developer.android.com/reference/kotlin/java/lang/Number.html)[y](index.md#-1223893684%2FProperties%2F-89531115) |

## Extensions

| Name | Summary |
|---|---|
| [map](index.md#1861158941%2FExtensions%2F-89531115) | [androidJvm]<br>final [Keypoint](index.md)[map](index.md#1861158941%2FExtensions%2F-89531115)([Matrix](https://developer.android.com/reference/kotlin/android/graphics/Matrix.html)tr) |
