//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Keypoints](index.md)/[getEdges](get-edges.md)

# getEdges

[androidJvm]\

final [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)&gt;&gt;[getEdges](get-edges.md)()

Information about keypoint skeleton (lines connecting keypoints). A useful visual construct.

edges contains list of indices. E.g. if

edge = [[0,4],[2,1]]

Then keypoint at 0th index and 4th index is to be connected by a line. Same goes for keypoint at index 2 and index 1.

See [https://cocodataset.org/#format-data] for further info
