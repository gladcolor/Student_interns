# Student_interns

## Task 1 Image Downloading
Downloading at least 10000 images from `house_location.csv`. You can use `GPano.shootLonlats()` in GPano.py from https://github.com/gladcolor/StreetView. You can also use  `GPano.shootLonlats_mp()` which implemented with Multiple Processing.


# Task 2 Image classification
Building a classifier to detect the number of storie of a house. `house_location.csv` have a `story` column. Please use Pytorch. If you do not fimiliar with Pytorch, following this great tutorial:  

[Pytorch fine-tuning](https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html)

Images from Task 1 should be divided into training set (70%) and test set (30%). Each training sample contains an image and a class label. The label represent the number of stories. For example:

| Class label | Number of stories |
| --- | ----------- |
| 1 | 1 |
| 2 | 2 |
| 3 | 2.5 |
| 4 | 3 |

## Task 3 Building detection in street view image
Using any deep learning method by Pytorch to detect houses/buildings in the downloaded images.

Youc can have a look at [ADK20k dataset](http://groups.csail.mit.edu/vision/datasets/ADE20K/dataset_browser/)

![](/img/building_ade20k.jpg)

![](/img/house_ade20k.jpg)

## Task 4 Image Segmentation
Using GluonCV (MXNet) to segment street view images. Load five pre-trained models (fcn_resnet101_ade, psp_resnet101_ade, deeplab_resnet101_ade, psp_resnet101_citys, and deeplab_v3b_plus_wideresnet_citys), then inference the images in `StreetViewImage.zip`. Follow the toturials in [here](https://gluon-cv.mxnet.io/build/examples_segmentation/index.html).

After having the segmentation result, mosaic the results of the same image together, like this:
![](/img/mosaic.jpg)

