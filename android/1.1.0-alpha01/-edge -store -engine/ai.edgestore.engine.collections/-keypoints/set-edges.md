//[Edge Store Engine](../../../index.md)/[ai.edgestore.engine.collections](../index.md)/[Keypoints](index.md)/[setEdges](set-edges.md)

# setEdges

[androidJvm]\

final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[setEdges](set-edges.md)([List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)&gt;&gt;edges)

Information about keypoint skeleton (lines connecting keypoints). A useful visual construct.

edges contains list of indices. E.g. if

edge = [[0,4],[2,1]]

Then keypoint at 0th index and 4th index is to be connected by a line. Same goes for keypoint at index 2 and index 1.

See [https://cocodataset.org/#format-data] for further info
