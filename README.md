# Medical-Image-Analysis
Designing and developing a CNN for malaria image analysis

# Data Characteristics
Size – 407.5 MB
Source – National Library of Medicine
Shape –  The dataset contains a total of 27,558 cell images with equal instances of parasitized and uninfected cells.
Labelled Target – (Parasitized/Uninfected)

# Steps
1. Downloaded data and cleaned and organized the images.

2. Feature extraction using pretrained neural networks - VGG 16
![Alt text](FE.png?raw=true "FE.png")

3. Modelling using different models - Basic Vs. Multilayer Perceptron
# Best Model
![Alt text](BestModel.png?raw=true "BestModel.png")

4. Visuvalize the predictions
![Alt text](Prediction.png?raw=true "Prediction.png")

5. Future Work:

        Try Conv2d and Max Pooling with strides
        Augment the data to prevent overfitting 

