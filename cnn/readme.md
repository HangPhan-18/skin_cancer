## CNN(Convolution Neural Network)
In deep learning, a convolution neural network is a class of artificial neural network(ANN), most commonly applied to analyzed visual imagery. CNNs are also known as Shift Invariant or Space Invariant Artificial Neural Networks (SIANN). based on the shared-weight architecture of the convolution kernels or filters that slide along input features and provide translation-equivariant responses knowns as feature maps. Counter-intuitively, most convolution neural networks are only equivariant, as opposed to invariant, to translation. They have applications in image and video recognition, image segmentation, medical image analysis, natural language processing, brain-computer interfaces, and financial time series.
## Building Blocks
# Architecture Convolution Neural Network
![image](https://user-images.githubusercontent.com/89575378/163771302-32fb640d-b9b7-4bed-bfa1-7e35777d9bda.png)

There are two main parts to a CNN architecture
+A convolution tool that separates and identifies the various features of the image for  analysis in a process called as Feature Extraction.
+ A fully conected layer that utilizes the output from tthe convolution process anf predict the class of the iage based on the features extracted in previous stages.
# Convolution Layers 
There are three types of layers that make up the CNN which are the convolutional layers, pooling layers, and fully-connected (FC) layers. When these layers are stacked, a CNN architecture will be formed. In addition to these three layers, there are two more important parameters which are dropout layer and the activation function which are defined below.
1. Convolution Layer
This layer is the first layer that is used to extract the various features from the input images. In this layer, the mathematical operation of convolution is performed between the input image and a filter of a particular size MxM. By sliding the filter over the input image, the dot product is taken between the filter and the parts of the inout image respect to the size of the filter (MxM).

The output is termed as the Feature map which gives us information about the image such as the concerns and edges. Later, this feature map is fed to other layers to learn several other features of the input image.

2. Pooling Layer
In most cases, c Convolution Layer is followed by a Pooing Layer. The primary aim of this layer is to decrease the size of the convolved feature map to reduce the computational cost. This is performed by decreasing the connections between layers and independently operates on each feature map. Depending upon method used, there are several tyoes of Pooing operations.
