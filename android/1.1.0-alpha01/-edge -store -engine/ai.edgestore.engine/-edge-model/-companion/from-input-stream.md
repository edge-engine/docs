//[Edge Store Engine](../../../../index.md)/[ai.edgestore.engine](../../index.md)/[EdgeModel](../index.md)/[Companion](index.md)/[fromInputStream](from-input-stream.md)

# fromInputStream

[androidJvm]\

final [EdgeModel](../index.md)[fromInputStream](from-input-stream.md)([InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)inputStream)

Factory method to get [EdgeModel](../index.md) for inference

*Note: This is a convenience method. This method will read the whole input stream* into memory and does not provide any efficiency benefits.

## Parameters

androidJvm

| | |
|---|---|
| inputStream | Raw [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html) to model.edgem. |
