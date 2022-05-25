# Semantic-Segmentation 
Abstract: this repo shows how to predict masks with pytorch of any class/classes (in my case it's dog & background, but it easy to modificate and/or train using COCO dataset for another class).

 - deeplabv3_resnet50 - IoU 0.7

## Plan of Research:
First, let's identify the main architecture. deeplabv3_resnet50 is the best in pursuance of IOU metrics. Next we need to choose loss function, usually for segmentation people use CrossEntropyLoss, but also we would try DiceBCELoss.

So:
 - Architecture: deeplabv3_resnet50
 - Loss function: CrossEntropyLoss and/or DiceBCELoss
 - Optimizer: Adam, lr=1e-3

## Results

Example 1:
