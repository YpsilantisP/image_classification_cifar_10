# image_classification_cifar_10

# Project Plan
<br>
<br>

## __<font color='salmon'> Description </font>__

* In this classification problem, a Convolutional Neural Network has been developed to classify images from the CIFAR10 dataset according to the pre-set labels.

* Two different approaches have been followed; first, without applying data augmentation and second with applying data augmentation.

<br>
<br>

## __<font color='salmon'> The Data</font>__
* This project uses the CIFAR-10 dataset from pytorch (university of Toronto)
* This dataset has 60000 32x32 colour images. There are 50000 training images and 10000 test images.
* It has the classes: `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`. 
* [CIFAR10 pytorch](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html?highlight=cifar)
<br>
<br>

## __<font color='salmon'> Sections </font>__


* Imports.<br>
* Defining of functions:
    * getDataset
    * getTrainValidSampler
    * NetworkCnn
* Training without data augmentation
* Training with data augmentation
* Conclusion
<br>
<br>

## __<font color='salmon'> Notes</font>__
* This project is using GPU on google colab.
* To reproduce this code it is suggested to use a GPU as the computational time is too high when run on CPU.
* Install project requirements
   * `pip install -r requirements.txt` 
