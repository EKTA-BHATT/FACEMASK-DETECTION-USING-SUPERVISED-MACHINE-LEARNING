# FACEMASK-DETECTION-USING-SUPERVISED-MACHINE-LEARNING
A Machine Learning model to detect if a person is wearing face-mask or not

The World Health Organization (WHO) has declared the new coronavirus outbreak, a “Pandemic”
Common signs of infection include fever, coughing and breathing difficulties. In severe cases, it can cause pneumonia and death [1].
While researchers continue to learn more about the coronavirus that causes COVID-19, it is extremely important to maintain safety measures until a vaccine is ready. Wearing a facemask is one of the most effective ways to prevent the spread of the virus. 


# HOW?
The answer lies in technology. 
One of the way to prevent this spread is to wear facemask and use sanitizers. 
As the use sanitizers cannot be tracked, its not the same for facemask. The use of facemask can be tracked with the help of Machine learning. 
This ML model can be implemented into any system, as the model is quite light, fast and accurate. 

# CONVOLUTIONAL NEURAL NETWORK
Convolutional Neural Networks (CNN) are neural networks most commonly used to analyze images. 
A CNN receives an image as an input in the form of a 3D matrix. 
The first two dimensions corresponds to the width and height of the image in pixels while the third one corresponds to the RGB values of each pixel.
CNNs consist of the following sequential modules (each one may contain more than one layer) [3]

1. Convolution
2. ReLU activation function
3. Pooling
4. Fully connected layers
5. Output layer

# PROPOSED MODEL
![MODEL BLOCK DIG](https://user-images.githubusercontent.com/80860185/111623554-89578280-8810-11eb-891f-68cd50b8e06d.png)

# MODEL DEVELOPMENT
Our model is completely based on CNN model with various layers but there is a small change in it. We are neglecting the convolution layer over here and are using MobileNetV2 instead of it. MobileNetV2 is very fast when compared to convolution layer and also it is a very effective feature extractor for object detection and segmentation. We are basically creating a base model using MobileNetV2 and then we pass it into the head neural network.
We are using layers like Pooing2D, Flatten, Dense, Dropout in the CNN
![New document 1 2020_11_23_02_24_55 0](https://user-images.githubusercontent.com/80860185/111623674-ae4bf580-8810-11eb-9ae1-5ec1ac906aab.png)


# RESULT
The CNN model is successfully developed to detect if a person is wearing a mask or not. 
Being very light and accurate this model can be incorporated with any basic hardware components and therefore having a large variety of implementation scope.

# PRACTICAL HARDWARE IMPLEMENTATION
The practical hardware implementation for this model is very flexible. 
As we are creating our complete model on MobileNetV2, is take very less memory and also the number of input parameters is lesser.
 Hence it makes it easy to just incorporate this model to any type of hardware processor.
The simplest implementation can be the use of Raspberry pi and some other modules.
This model can be installed along with the CCTV cameras in malls, supermarkets, etc. Hence making it quite a versatile model.


THANK YOU SO MUCH !!! :)
