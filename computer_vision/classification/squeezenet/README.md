*******************************************************************************
##### Structure of the directory for storing model files
```
computer_vision
   |-- classification
       |-- squeezenet
            |--squeezenet.om
            |--README.md
   |-- object_detect
   |-- segmentation
```
*******************************************************************************

##### Original Network Link:
https://github.com/DeepScale/SqueezeNet/tree/master/SqueezeNet_v1.1

##### Pre-trained Model Link:
https://github.com/DeepScale/SqueezeNet/tree/master/SqueezeNet_v1.1

##### Input Data Description:
The input image should be resized to 227*227 pixels, and padding to 256*224 pixels, YUV420SP_U8.

##### Out Data Description:
The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

##### Custom Operator:
Not included

##### Versions that have been verified:
- Atlas 200