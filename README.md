# Lawn Weed Detector

- Author:  Chiyuan Cheng (cyuancheng AT gmail DOT com) 
- Last updated: Aug 29, 2019

## Table of Contents

1. [Objective](#objective)
2. [Data](#data)
3. [Results](#results)
4. [License](#licensing)


## Objective <a name="objective"></a>

To create an AI detector for common lawn weeds using computer vision and deep learning. The 7 common lawn weeds are:
- Annual Bluegrass
- Crabgrass
- Creeping Charlie
- Dandelion
- Dollar weed
- Oxalis
- White clover


## Data <a name="data></a>

The training and test imaging dataset was collected from Google image and stored on google drive for analysis. 
![7 common lawn weeds](/image_weed.JPG)


## Result <a name="method></a>
 - Image augmentation was used to improve the performance of deep learning in imaging classification.
 - Dataset contains 1830 training data and 457 testing data.
 - resnet50 was used for the deep learning model.
 - 95% accuracy can be achieved to predict the lawn weed.
 ![Confusion matrix](/confusion_matrix)

## License<a name="licensing"></a>

The credit was given fast.ai courses for the fast.ai package.
