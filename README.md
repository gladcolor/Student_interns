# Student_interns

## Task 1
Downloading at least 10000 images from `house_location.csv`. You can use `GPano.shootLonlats()` in GPano.py from https://github.com/gladcolor/StreetView. You can also use  `GPano.shootLonlats_mp()` which implemented with Multiple Processing.


# Task 2
Building a classifier to detect the number of storie of a house. `house_location.csv` have a `story` column. Please use Pytorch. If you do not fimiliar with Pytorch, following this great tutorial:  

[Pytorch fine-tuning](https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html)

Images from Task 1 should be divided into training set (70%) and test set (30%). Each training sample contains an image and a class label. The label represent the number of stories. For example:

| Class label | Number of stories |
| --- | ----------- |
| 1 | 1 |
| 2 | 2 |
| 3 | 2.5 |
| 4 | 3 |

## Task 3
Using any deep learning method by Pytorch to detect houses/buildings in the downloaded images.

Youc can have a look at [ADK20k dataset](http://groups.csail.mit.edu/vision/datasets/ADE20K/dataset_browser/)

![](/img/building_ade20k.jpg)

![](/img/house_ade20k.jpg)

