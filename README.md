# Facial Expression Recognition

This repository is to do facial expression prediction by fine-tuning ResNet-18 with FER-2013 Faces Database.

![data-original](https://user-images.githubusercontent.com/11619444/127019677-db8141b8-ab28-46de-a695-237fa894e227.png)
(Image source: www.kaggle.com)

# Notebooks
### [FacialExpressionRecognition.ipynb](https://github.com/mansikataria/FacialExpressionRecognition/blob/main/FacialExpressionRecognition.ipynb)

**Keras** is used to create and train a **CNN** model with **BatchNorm**. Data is augmented using random rotation, width/height shift, zoom, horizontal flip before training. Model is trained for 50 epochs with batch size 64. More accuracy can be achieved by training for more epochs.

Test Accuracy achieved: 65.45% 

Loss & Accuracy Graph: 

![image](https://user-images.githubusercontent.com/11619444/127021241-aa04a488-e947-4b50-9f59-4f62148750fc.png)


