# driver-activity-recognition

The MobileNetV3Large integrated with Convolutional Block Attention Mechanism (CBAM) uses State Farm Dataset to train and evaluate on different driver activities. This is a multi-class classification research conducted under limited training parameters.

Similarly, the EfficientNetB3 model is also used to train and evaluate on the State Farm Dataset.

We conduct analysis on both the light weight models and analyse the dataset ambiguity to differentiate few driver activites.

CBAM_MobileNetV3Large_V1.0.ipynb and CBAM_EfficientNetB3_V1.0.ipynb are the files where experiments are conducted for State Farm Dataset.

These models are also trained and tested on AUC Driver Dataset Camera 2 where the images are of different camera angle and position. The images are also taken in opposite direction to that of State Farm data. The experiment code is available in CBAM_MobileNetV3Large_AUCCAM2_V1.1.ipynb and CBAM_EfficientNetB3_AUCCAM2_V1.1.ipynb files.



References:
State Farm Dataset : https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data 

AUC Driver Dataset : https://heshameraqi.github.io/distraction_detection

