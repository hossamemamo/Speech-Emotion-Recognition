# Speech-Emotion-Recognition Using 2 diffrent CNN models with 2-D convolution 
# Architecture

# Model 1
* 2 Parallel CNNs
![](./Assets/ParaNet.png)

1. AlexNet laid the groundwork for enhancing feature maps by stacking CNN layers and expanding channels.
2. Inception and GoogLeNet introduced the idea of parallelizing CNN layers to diversify the learned features.
3. VGGNet demonstrated the effectiveness of using fixed-sized kernels that we use in each parallel network.
4. LeNet architecture inspired the sequence of operations: Convolutional layer, pooling layer, convolutional layer, pooling layer and a fully connected layer.

# Results  Accuracy : 64.26 %
![](./Assets/ParaNetResults.jpg)


# Model 2
* 2 Parallel CNNs + Transformer Encoder
1. Transformer-Encoder layer from the Attention is All You Need paper


 Transformers allows for capturing both local and global dependencies in the input data. This flexibility enables the model to learn complex patterns and relationships at various scales, enhancing its ability to model intricate structures within the data.
![](./Assets/ParaNet%2Btransformer.png)

# Results  Accuracy : 66.23 %
![](./Assets/ParaNet%2BTransformersResult.jpg)

