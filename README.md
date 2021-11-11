# Steel-Defect-Detection---Image-Segmentation-using-Keras-and-Tensorflow

# 1. Business Problem
Steel is one of the most important building materials of modern times. Steel buildings are resistant to natural and man-made wear which has made the material ubiquitous around the world. The production process of flat sheet steel is especially delicate. From heating and rolling, to drying and cutting, several machines touch flat steel by the time it's ready to ship. 
Today, Severstal is leading the charge in efficient steel mining and production. Severstal is now looking for machine learning to identify defects in steel which will help make production of steel more efficient. This competition will help engineers improve the defect detection algorithm by localizing and classifying surface defects on a steel sheet.

# 2. Source of Data
It is a Kaggle competition held by Severstal. Data is available at https://www.kaggle.com/c/severstal-steel-defect-detection/data

# 3. Data Overview
train_images/ - folder with 12568 .jpg training images.

test_images/ - folder with 5516 .jpg test images (we are segmenting and classifying these images).

train.csv - training annotations which provide segments for defects with total 4 defect classes (ClassId=[1,2,3,4]).

sample_submission.csv - a sample submission file in the correct format (for each ImageId 4 rows, one for each of the 4 defect classes).

Each image is of 256x1600 resolution

