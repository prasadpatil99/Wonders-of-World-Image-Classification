# MultiClass Image Classification
Aim to make Artificial Neural Network to learn *Wonders Across World*
> Artificial Neural Network are inspired by human brain,<br>
As inspired they are not complete biologically similar but learn correlations of images with help of multiple weights dedicated to the input according to its importance and according to the type of Neural Network characteristic.
## Data Preprocessing
Data Gathered by downloading Google Images with [Python Library](https://pypi.org/project/google_images_download/) 

## CNN
Model consist of learning from Convolution Neural Network (CNN).<br>
CNN contains multiple layers like *Convolution Layer, Maxpooling Layer, Average Pooling, Flatten Layer.<br>*
 - **Convolution Layer** - *Convolution layer contains set of filters whose parameters are smaller than input. This filter is slided across the width and height of the input images and the dot products are calculated.Since the size of filter are smaller than input, each neuron learns that particular region. In short, the filter size is equal to size of neuron. Hence neurons here contains summary of input images without any loss.*
 - **Maxpooling Layer** - *Maxpooling is similar to convolution layer where image is slided through out, only difference is there is no matrix multiplication or dot product with filter instead maxpooling returns the feature having maximum value or greater correlation in an image. Hence neurons here hold most significance and sharpest feature of an image*
 ![](https://miro.medium.com/max/1421/1*2SWb6CmxzbPZijmevFbe-g.jpeg)
 - **Flattening Layer** - *It is used at a final stage to convert multi dimensional vector to one dimensional or in a single column* 

*For executing CNN in [Google Colab](https://colab.research.google.com/github/prasadpatil99/multiclass_image_classification/blob/master/Data%20Processing.ipynb)*<br>


## Transfer Learning 
Transfer Learning is a process where already pretrained model on one task is repurposed for a second similar/related task.<br> It gives features like *saving training time, better performance without needing lot of data*. Weights of pretrained model are already trained well so it can cut short time and computational cost. <br>
[Here](https://www.it4nextgen.com/keras-image-classification-models/) is list of best pretrained models for transfer learning. <br>
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

## Dataset
*Dataset can be obtained from [here](https://drive.google.com/open?id=1fMHqRMeiq-i5iaNryW1oqmD5tlcDWOow)*

## Dependencies 
``` sh
$ pip3 install --user --upgrade tensorflow
$ pip install Keras
$ pip install glob2
$ pip install opencv2
$ pip install scikit-learn
```

## Reference
 - https://keras.io/ <br>
 - Readme - https://github.com/flekhulani/Car-Recognition

## Author
- *Prasad Patil*
