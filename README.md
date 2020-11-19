# Pneumonia-Detection-Using-CNN
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
<a><img src="https://img.shields.io/badge/numpy%20-%23013243.svg?&style=for-the-badge&logo=numpy&logoColor=white" /></a>
<a><img src="https://img.shields.io/badge/TensorFlow%20-%23FF6F00.svg?&style=for-the-badge&logo=TensorFlow&logoColor=white" /></a>
<a><img src="https://img.shields.io/badge/Keras%20-%23D00000.svg?&style=for-the-badge&logo=Keras&logoColor=white"/></a>
<a><img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/></a></br>
# Objective
To make a classifier that is able to distinguish between a person who has Pneumonia and a normal person using the X-Rays of their Lungs. These X-Rays were taken during regular check ups of these patients.

# Some details about the data
![alt text](https://github.com/AM1CODES/Pneumonia-Detection-using-chest-X-Ray/blob/main/Data_Example.png) <br>
The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

# Data set

This data set was taken off Kaggle. You can use the following link to get the data. <br>
Link - https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

# Results
Our model was able to distinguish between the patients that have Pneumonia successfully. The model gave an accuracy around 96% on the training data and had a validation accuracy of 82%. It was fed an image that it had never seen previously and made the correct prediction. But, i feel there is still some room for improvement.
