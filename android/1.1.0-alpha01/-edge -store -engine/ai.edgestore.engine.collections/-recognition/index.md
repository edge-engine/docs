//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Recognition](index.md)

# Recognition

[androidJvm]\
public final class [Recognition](index.md)

A result returned by a EdgeModel describing what was recognized.

This is a generalized class to encompass common computer vision detections. All of the elements are optional because a Model may not be designed to provide all the results. Common results that you can  expect for the tasks:

Classification ->[id](index.md#125604180%2FProperties%2F-89531115),name,[displayName](index.md#-731949090%2FProperties%2F-89531115),[confidence](index.md#36501701%2FProperties%2F-89531115)

Object Detections ->[id](index.md#125604180%2FProperties%2F-89531115),name,[displayName](index.md#-731949090%2FProperties%2F-89531115),[confidence](index.md#36501701%2FProperties%2F-89531115),[location](index.md#1671936634%2FProperties%2F-89531115)

Pose Estimation ->[id](index.md#125604180%2FProperties%2F-89531115),name,[displayName](index.md#-731949090%2FProperties%2F-89531115),[confidence](index.md#36501701%2FProperties%2F-89531115),[location](index.md#1671936634%2FProperties%2F-89531115) (maybe),[keypoints](index.md#-1734550679%2FProperties%2F-89531115)

Other Tasks (coming soon)

## Constructors

| | |
|---|---|
| [Recognition](-recognition.md) | [androidJvm]<br>[Recognition](index.md)[Recognition](-recognition.md)([Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)id, [String](https://developer.android.com/reference/kotlin/java/lang/String.html)displayName, [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)confidence, [RectF](https://developer.android.com/reference/kotlin/android/graphics/RectF.html)location, [Keypoints](../-keypoints/index.md)keypoints, [NLAnswer](../-n-l-answer/index.md)answer, [Color](https://developer.android.com/reference/kotlin/android/graphics/Color.html)color) |

## Functions

| Name | Summary |
|---|---|
| [getAnswer](get-answer.md) | [androidJvm]<br>final [NLAnswer](../-n-l-answer/index.md)[getAnswer](get-answer.md)() |
| [getClassificationResult](get-classification-result.md) | [androidJvm]<br>final [ClassificationResult](../../ai.edgestore.engine.collections.tasks/-classification-result/index.md)[getClassificationResult](get-classification-result.md)() |
| [getColor](get-color.md) | [androidJvm]<br>final [Color](https://developer.android.com/reference/kotlin/android/graphics/Color.html)[getColor](get-color.md)() |
| [getConfidence](get-confidence.md) | [androidJvm]<br>final [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[getConfidence](get-confidence.md)()<br>A sortable score for how good the recognition is relative to others. Higher should be better. |
| [getDisplayName](get-display-name.md) | [androidJvm]<br>final [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[getDisplayName](get-display-name.md)()<br>Display name for the recognition. |
| [getId](get-id.md) | [androidJvm]<br>final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[getId](get-id.md)()<br>A unique identifier for what has been recognized. Specific to the class, not the instance of the object. |
| [getKeypointResults](get-keypoint-results.md) | [androidJvm]<br>final [KeypointResults](../../ai.edgestore.engine.collections.tasks/-keypoint-results/index.md)[getKeypointResults](get-keypoint-results.md)() |
| [getKeypoints](get-keypoints.md) | [androidJvm]<br>final [Keypoints](../-keypoints/index.md)[getKeypoints](get-keypoints.md)() |
| [getLocation](get-location.md) | [androidJvm]<br>final [RectF](https://developer.android.com/reference/kotlin/android/graphics/RectF.html)[getLocation](get-location.md)()<br>Optional location within the source image for the location of the recognized object. |
| [getObjectDetectionKeypointResults](get-object-detection-keypoint-results.md) | [androidJvm]<br>final [ObjectDetectionKeypointResults](../../ai.edgestore.engine.collections.tasks/-object-detection-keypoint-results/index.md)[getObjectDetectionKeypointResults](get-object-detection-keypoint-results.md)() |
| [getObjectDetectionResult](get-object-detection-result.md) | [androidJvm]<br>final [ObjectDetectionResults](../../ai.edgestore.engine.collections.tasks/-object-detection-results/index.md)[getObjectDetectionResult](get-object-detection-result.md)() |
| [map](map.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[map](map.md)([Matrix](https://developer.android.com/reference/kotlin/android/graphics/Matrix.html)tr) |
| [setLocation](set-location.md) | [androidJvm]<br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setLocation](set-location.md)([RectF](https://developer.android.com/reference/kotlin/android/graphics/RectF.html)location)<br>Optional location within the source image for the location of the recognized object. |
| [toString](to-string.md) | [androidJvm]<br>[String](https://developer.android.com/reference/kotlin/java/lang/String.html)[toString](to-string.md)() |

## Properties

| Name | Summary |
|---|---|
| [answer](index.md#-120122607%2FProperties%2F-89531115) | [androidJvm]<br>private final [NLAnswer](../-n-l-answer/index.md)[answer](index.md#-120122607%2FProperties%2F-89531115) |
| [classificationResult](index.md#67334988%2FProperties%2F-89531115) | [androidJvm]<br>private final [ClassificationResult](../../ai.edgestore.engine.collections.tasks/-classification-result/index.md)[classificationResult](index.md#67334988%2FProperties%2F-89531115) |
| [color](index.md#-1657574872%2FProperties%2F-89531115) | [androidJvm]<br>private final [Color](https://developer.android.com/reference/kotlin/android/graphics/Color.html)[color](index.md#-1657574872%2FProperties%2F-89531115) |
| [confidence](index.md#36501701%2FProperties%2F-89531115) | [androidJvm]<br>private final [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)[confidence](index.md#36501701%2FProperties%2F-89531115)<br>A sortable score for how good the recognition is relative to others. Higher should be better. |
| [displayName](index.md#-731949090%2FProperties%2F-89531115) | [androidJvm]<br>private final [String](https://developer.android.com/reference/kotlin/java/lang/String.html)[displayName](index.md#-731949090%2FProperties%2F-89531115)<br>Display name for the recognition. |
| [id](index.md#125604180%2FProperties%2F-89531115) | [androidJvm]<br>private final [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[id](index.md#125604180%2FProperties%2F-89531115)<br>A unique identifier for what has been recognized. Specific to the class, not the instance of the object. |
| [keypointResults](index.md#-125451738%2FProperties%2F-89531115) | [androidJvm]<br>private final [KeypointResults](../../ai.edgestore.engine.collections.tasks/-keypoint-results/index.md)[keypointResults](index.md#-125451738%2FProperties%2F-89531115) |
| [keypoints](index.md#-1734550679%2FProperties%2F-89531115) | [androidJvm]<br>private final [Keypoints](../-keypoints/index.md)[keypoints](index.md#-1734550679%2FProperties%2F-89531115) |
| [location](index.md#1671936634%2FProperties%2F-89531115) | [androidJvm]<br>private [RectF](https://developer.android.com/reference/kotlin/android/graphics/RectF.html)[location](index.md#1671936634%2FProperties%2F-89531115)<br>Optional location within the source image for the location of the recognized object. |
| [objectDetectionKeypointResults](index.md#-797757776%2FProperties%2F-89531115) | [androidJvm]<br>private final [ObjectDetectionKeypointResults](../../ai.edgestore.engine.collections.tasks/-object-detection-keypoint-results/index.md)[objectDetectionKeypointResults](index.md#-797757776%2FProperties%2F-89531115) |
| [objectDetectionResult](index.md#-498019384%2FProperties%2F-89531115) | [androidJvm]<br>private final [ObjectDetectionResults](../../ai.edgestore.engine.collections.tasks/-object-detection-results/index.md)[objectDetectionResult](index.md#-498019384%2FProperties%2F-89531115) |
