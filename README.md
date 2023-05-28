# COVIDVisionX_ML
Machine Learning Models tested for FYP-23-S1-01

Link to Dataset used: 
https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia

Dataset of chest X-ray images from Kaggle
- Organized into 2 folders (train, test)
- Contain 3 subfolders (COVID19, PNEUMONIA, NORMAL)
- Total of 6432 x-ray images in JPG image format

Training data (80% of total images)
COVID19: 460 images,
NORMAL: 1266 images,
PNEUMONIA: 3418 images

Testing data (20% of total images)
COVID19: 116 images,
NORMAL: 317 images,
PNEUMONIA: 855 images


Additional models tested:

Links to other datasets tested:
https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
https://data.mendeley.com/datasets/rscbjbr9sj/2

Methods used to expand dataset (CNN):
CNN_model.ipynb used image augmentation to artificially expand the dataset.

Other CNN models tested made use of transfer learning from the Imagenet dataset. Imagenet is a widely used dataset that provides labeled images for training deep learning models like ResNet50 and VGG19, which was tested in our project. These models are then fine-tuned or used as a starting point for various image-related tasks, benefiting from the pre-learned features from Imagenet. Using transfer learning reduces training time and data amount requirements, and lowers the generalisation error rate.
