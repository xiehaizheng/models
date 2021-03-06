*******************************************************************************
##### Structure of the directory for storing model files
```
computer_vision
   |-- classification
       |-- vgg16
            |--vgg16.om
            |--README.md
   |-- object_detect
   |-- segmentation
```
*******************************************************************************

##### Original Network Link:
https://github.com/davidgengenbach/vgg-caffe/blob/master/model/VGG_ILSVRC_16_layers_deploy.prototxt

##### Pre-trained Model Link:
http://www.robots.ox.ac.uk/~vgg/software/very_deep/caffe/VGG_ILSVRC_16_layers.caffemodel

##### Input Data Description:
The input image should be resized to 224*224 pixels, and padding to 256*224 pixels, YUV420SP_U8.

##### Out Data Description:
The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

##### Custom Operator:
Not included

##### Versions that have been verified:
- Atlas 200
