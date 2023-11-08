## IMAGE CLASSIFICATION USING MOBILENET
The objective of this notebook is to classify the histopathological images using MobileNet, which is a simple but efficient and not very computationally intensive convolutional neural networks. The dataset used for this classification model is the LC25000 LUNG AND COLON HISTOPATHOLOGICAL IMAGE DATASET. This dataset contains 25,000 histopathological images with 5 classes, each with 5,000 images, being:

Lung benign tissue
Lung adenocarcinoma
Lung squamous cell carcinoma
Colon adenocarcinoma
Colon benign tissue
All images are 768 x 768 pixels in size and are in jpeg file format.

### MobileNet Model Architecture

 Neural Network Architecture of MobileNet. a Depthwise Convolution layer. b Pointwise Convolution layer. c Depthwise Separable convolutions with Depthwise and Pointwise layers followed by batchnorm and ReLU
