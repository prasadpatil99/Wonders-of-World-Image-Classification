## Aim to make Artificial Neural Network to learn Wonders Across World

> Artificial Neural Network are inspired by human brain,
As inspired they are not completely biologically similar but learn correlations of images with help of multiple weights dedicated to the input according to its importance. 
Despite of this multiple layers like Convolution ,MaxPooling ,Dense ,Flatten Layer are defined to complete the learning process, these layers can change accordingly for better learning depicted by accuracy.


### Convolution Layer
Input images due to noise or unimportant parts in image can hold unsignificance memory and loss of computational power, here convolutional layer helps in. Convolution layer contains set of filters whose parameters are smaller than input volume. 
![](https://cdn-media-1.freecodecamp.org/images/Gjxh-aApWTzIRI1UNmGnNLrk8OKsQaf2tlDu)
This filter is slided across the width and height of the input images and the dot products are calculated. 
![](https://miro.medium.com/max/447/1*nYf_cUIHFEWU1JXGwnz-Ig.gif)
Since the size of filter are smaller than input, each neuron learns that particular region. In short, the filter size is equal to size of neuron. Hence neurons here contains summary of input images without any loss.


### Max Pooling Layer
Maxpooling is similar to convolution layer where image is slided through out, only difference is there is no matrix multiplication or dot product with filter instead maxpooling returns the feature having maximum value or greater correlation in an image. Hence neurons here hold most significance and sharpest feature of an image

****imgimgimgimgimgimgimgigmgimgimgimgimgimigmigmigmimgimigmigmimgimgimimgimgimgmiimi*******



### Dense Layer
Regular hidden layer carrying weights from input neuron to output neuron

### Activation function 
Activation function is a node that is put at the end of or in between Neural Networks. They help to decide that should neuron activated or not. The activation function is the non linear transformation that is done over the input images. Types of activation funtion [are](https://keras.io/activations/)

### Flattening Layer
Flattening Layer is used at a final stage to convert multi dimensional vector to one dimensional or a single column  
![](https://miro.medium.com/max/481/1*GLQjM9k0gZ14nYF0XmkRWQ.png)

### Data Sample
1 | 2 | 3 |
|---|---|---|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/0_out.png)  | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/1_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/2_out.png)|
|$(result_1)|$(result_2)|$(result_3)|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/4_out.png)  | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/5_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/6_out.png)|
|$(result_4)|$(result_5)|$(result_6)|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/8_out.png)  | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/9_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/10_out.png)|
|$(result_7)|$(result_8)|$(result_9)|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/12_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/13_out.png)| ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/14_out.png)|
|$(result_10)|$(result_11)|$(result_12)|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/16_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/17_out.png)|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/18_out.png) |
|$(result_13)|$(result_14)|$(result_15)|
|![image](https://github.com/foamliu/Car-Recognition/raw/master/images/0_out.png)  | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/1_out.png) | ![image](https://github.com/foamliu/Car-Recognition/raw/master/images/2_out.png)|
|$(result_16)|$(result_17)|$(result_18)|


Author
- [Prasad Patil](https://kaggle.com/prasadpatil99)


