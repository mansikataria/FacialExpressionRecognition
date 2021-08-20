# Facial Expression Recognition

This repository is to do facial expression prediction by fine-tuning ResNet-18 with FER-2013 Faces Database.

![data-original](https://user-images.githubusercontent.com/11619444/127019677-db8141b8-ab28-46de-a695-237fa894e227.png)
(Image source: www.kaggle.com)

# Notebooks

### [FERResNet.ipynb](https://github.com/mansikataria/FacialExpressionRecognition/blob/main/FERResNet.ipynb)

**Pytorch** is used to create **ResNet18** model. **RandomCrop** and **HorizontalFlip** are applied on data before training. The model is trained for 200 epochs with batch size 32.

**Private Test Accuracy: 73%**

Loss Graph:
![image](https://user-images.githubusercontent.com/11619444/127031833-2b114201-88fb-4c0b-bf38-1777d77cde06.png)

Accuracy Graph:
![image](https://user-images.githubusercontent.com/11619444/127031883-45cecb3c-af0a-4e9e-862c-e1e5aca97501.png)

Confusion Matrix:
![image](https://user-images.githubusercontent.com/11619444/130183112-da057ab9-1f4a-4e62-9f4d-4ac8afb99319.PNG)


### [FacialExpressionRecognition.ipynb](https://github.com/mansikataria/FacialExpressionRecognition/blob/main/FacialExpressionRecognition.ipynb)

**Keras** is used to create and train a **CNN** model with **BatchNorm**. Data is augmented using random rotation, width/height shift, zoom, horizontal flip before training. Model is trained for 50 epochs with batch size 64. More accuracy can be achieved by training for more epochs.

**Private Test Accuracy: 65.45% **

Loss & Accuracy Graph: 

![image](https://user-images.githubusercontent.com/11619444/127021241-aa04a488-e947-4b50-9f59-4f62148750fc.png)


