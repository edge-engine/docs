//[Edge Store Engine](index.md)

# Edge Store Engine

[androidJvm]\
Visit our [landing page](https://www.edgestore.ai) to learn more about our product or directly visit our [store](https://store.edgestore.ai/) to browse various models. We support following domains in the current sdk version:

- 
   Image Processing
- 
   Text Processing
- 
   Audio Processing If your use case is not covered then please [contact us](https://www.edgestore.ai/about) and we will prioritise it over next update.

##  Installation

To install the sdk add following lines in your gradle app dependencies (hosted on Maven Central):

dependencies {\
    // other project dependencies ...\
    implementation "ai.edgestore:engine:1.1.0-alpha01"\
}

##  Quick Start

[Login/SignUp](https://store.edgestore.ai) at our [Edge Store](https://home.edgestore.ai) and find a model that you like. In this tutorial we will be running the amazing [Centernet Keypoints](https://store.edgestore.ai/home/model?model=centernet-keypoints) model. This model detects person's bounding box and keypoints.  Download the model and add the downloaded model.edgem file in you assets folder. edgem is our file extension for sdk compatible models. 

###  Running the Model

Following is the code to run the model:

####  Kotlin

val model = EdgeModel.fromAsset(context, "model.edgem")\
val bitmap: Bitmap = //your input image\
//Centernet keypoints only accepts single image\
val inputData = listOf(bitmap)\
val results: Recognitions = model.run(inputData)

####  Java

EdgeModel model = EdgeModel.fromAsset(context,"model.edgem");\
Bitmap bitmap = //your input image\
List&lt;Object&gt; inputData = Arrays.asList(bitmap);\
Recognitions results = model.run(inputData);

And thats it! You have successfully run an a complex AI model just in a few lines. Now it is time to visualize the results.

###  Visualizing the Results

To quickly visualize the results:

####  Kotlin

val resultsBitmap: Bitmap = results.drawOnBitmap(bitmap)

####  Java

Bitmap resultsBitmap=results.drawOnBitmap(bitmap,18.0F);

You can now add the resultsBitmap to your layout to quickly visualize the results. This will draw location of person, confidence of detection, and [keypoints](https://api.edgestore.ai/docs/sdk/android/-edge%20-store%20-engine/ai.edgestore.engine.collections/-keypoint/index.html) on the resultsBitmap.

you can also use results.drawOnCanvas function to draw on [Canvas](https://developer.android.com/reference/android/graphics/Canvas.html#Canvas()).

###  Interpreting and Using Results

The output *results* variable has type [Recognitions](https://api.edgestore.ai/docs/sdk/android/-edge%20-store%20-engine/ai.edgestore.engine.collections/-recognitions/index.html) that is a type of List. All the useful information the model provides is compacted into this variable. Not matter your use case the output of model will always be

For example if our model detects two persons in an image then results List will contain two elements. Each element is of type [Recognition](https://api.edgestore.ai/docs/sdk/android/-edge%20-store%20-engine/ai.edgestore.engine.collections/-recognition/index.html) and represents detection of each person

####  Kotlin

for (person in results) {\
    // how sure we are that this is actually a person. Value between 0 and 1, represents probability of detection\
    val confidence: Float = person.confidence!!\
    // the pixel location of person's bounding box in the image\
    val location: RectF = person.location!!\
    // Keypoints detected on the person\
    val keypoints: Keypoints = person.keypoints!!\
}

####  Java

for(Recognition person:results){\
        // how sure we are that this is actually a person. Value between 0 and 1, represents probability of detection\
        Float confidence=person.getConfidence();\
        // the pixel location of person's bounding box in the image\
        RectF location=person.getLocation();\
        // Keypoints detected on the person\
        Keypoints keypoints=person.getKeypoints();\
}

## Packages

| Name |
|---|
| [ai.edgestore.engine](-edge -store -engine/ai.edgestore.engine/index.md) |
| [ai.edgestore.engine.collections](-edge -store -engine/ai.edgestore.engine.collections/index.md) |
| [ai.edgestore.engine.collections.tasks](-edge -store -engine/ai.edgestore.engine.collections.tasks/index.md) |
| [ai.edgestore.engine.config](-edge -store -engine/ai.edgestore.engine.config/index.md) |
| [ai.edgestore.engine.graph](-edge -store -engine/ai.edgestore.engine.graph/index.md) |
| [ai.edgestore.engine.metadata](-edge -store -engine/ai.edgestore.engine.metadata/index.md) |
| [ai.edgestore.engine.protos](-edge -store -engine/ai.edgestore.engine.protos/index.md) |
| [ai.edgestore.engine.utils](-edge -store -engine/ai.edgestore.engine.utils/index.md) |
