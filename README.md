# COVID-19-pneumonia-claasification
**Pneumonia is an infection in one or both lungs. Bacteria, viruses, and fungi cause it. The infection causes inflammation in the air sacs in your lungs, which are called alveoli. The alveoli fill with fluid or pus, making it difficult to breathe.** 

**We presents methodology of a Deep Learning based chest X-ray image binary classifier model. This model takes the chest X-ray images as an input and results the class (Pneumonia affected or Normal). It is a threefold operation: At first the X-ray images are normalized using batch normalization technique and then two pretrained Residual Neural Networks, with 50 and 34 hidden layers is trained with 5910 normal and Pneumonia chest X ray images. Finally, the trained deep learning model predicts in real time. **


## Nomral Chest-Xray:

<img align="center" src="1.png" width="600" />

## pneumonia-bacteria Chest-Xray:

<img align="center" src="2.png" width="600" />

## pneumonia-Virus Chest-Xray:

<img align="center" src="3.png" width="600" />

## pneumonia-Virus-COVID-19 Chest-Xray:

<img align="center" src="4.png" width="400" />

## Information about Image:

- The dimensions of the image are 750 pixels width and 781 pixels height, one single color channel 
- The maximum pixel value is 255.0000 and the minimum is 0.0000 
- The mean value of the pixels is 134.5100 and the standard deviation is 54.1969 

<img align="center" src="5.png" width="200" />

## Top losses: 

<img align="center" src="6.png" width="600" />

## Confusion Matrix of classes: 

<img align="center" src="7.png" width="400" />
