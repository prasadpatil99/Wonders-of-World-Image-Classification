### MultiClass Image Classification
**Aim to make Artificial Neural Network to learn Wonders Across World**
> Artificial Neural Network are inspired by human brain,
As inspired they are not completely biologically similar but learn correlations of images with help of multiple weights dedicated to the input according to its importance. 
Despite of this multiple layers like Convolution, MaxPooling, Dense, Flatten Layer are defined to complete the learning process, these layers can change accordingly for better learning depicted by accuracy.

## Convolution Layer
Input images due to noise or unimportant parts in image can hold unsignificance memory and loss of computational power, here convolutional layer helps in. Convolution layer contains set of filters whose parameters are smaller than input volume.  
![](https://cdn-media-1.freecodecamp.org/images/Gjxh-aApWTzIRI1UNmGnNLrk8OKsQaf2tlDu)
This filter is slided across the width and height of the input images and the dot products are calculated.
![](https://miro.medium.com/max/447/1*nYf_cUIHFEWU1JXGwnz-Ig.gif)
Since the size of filter are smaller than input, each neuron learns that particular region. In short, the filter size is equal to size of neuron. Hence neurons here contains summary of input images without any loss.

### Max Pooling Layer
Maxpooling is similar to convolution layer where image is slided through out, only difference is there is no matrix multiplication or dot product with filter instead maxpooling returns the feature having maximum value or greater correlation in an image.
![](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/maxpool.png) 
Hence neurons here hold most significance and sharpest feature of an image

### Dense Layer
Regular hidden layer carrying weights from input neuron to output neuron

### Activation function 
Activation function is a node that is put at the end of or in between Neural Networks. They help to decide that should neuron activated or not. The activation function is the non linear transformation that is done over the input images. For types of activation funtion and its prameters [click](https://keras.io/activations/)

### Flattening Layer
Flattening Layer is used at a final stage to convert multi dimensional vector to one dimensional or a single column  
![](https://miro.medium.com/max/481/1*GLQjM9k0gZ14nYF0XmkRWQ.png)

## Data Preview
1 | 2 | 3 |
|---|---|---|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/venenzula.jpg)  | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/taj%20mahal.jpeg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/stonehenge.jpg)|
|Venezuela Angel Falls|Taj Mahal|Stonehenge|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/statue%20of%20liberty.jpg)  | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/santorini.jpg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/Chich-n%20Itz%20.jpg)|
|Statue of Liberty|Santorini|Chich-n Itz - Mexico|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/Christ%20the%20Reedemer%20Statue.jpg)  | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/Giant-s%20Causeway.jpg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/pyramid.jpg)|
|Christ the Reedemer Statue|Giant-s Causeway|Pyramids of Giza|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/niagara%20falls.jpg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/himalaya.jpg)| ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/blue%20grotto.jpg)|
|Niagara Falls|Himalaya|The Blue Grotto|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/eiffel%20tower.jpg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/great%20wall%20of%20china.jpg)|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/antartica.jpg) |
|Eiffel Tower|Great Wall of China|Antartica|
|![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/burj%20khalifa.jpeg)  | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/Roman%20Colosseum.jpg) | ![image](https://raw.githubusercontent.com/prasadpatil99/multiclass_image_classification/master/assets/machu%20picchu.jpg)|
|Burj Khalifa|Roman Colosseum |Machu Pichu|

**Dataset** can also be obtained from here
<br>
*Other dataset can be use by changing preference here*

### Dependencies 
``` sh
$ pip3 install --user --upgrade tensorflow
$ pip install Keras
$ pip install glob2
$ pip install opencv2
$ pip install scikit-learn
```

### References 
https://keras.io/ <br>
Readme - https://github.com/flekhulani/Car-Recognition

### Author
- Prasad Patil
