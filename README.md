# Pneumonia-Detection


![Pneumonia X-Ray Images](https://storage.googleapis.com/kaggle-datasets-images/661308/1166777/3f1da6fe1f06a4b75feab9d7a8aa8339/dataset-cover.png?t=2020-06-19-23-15-03)

Adapted version of Paul Mooney's 'Chest X-Ray Images (Pneumonia)' dataset, where the amount of observations for training and validation purposes was redistributed to allow for a more balanced machine learning exercise.

- **Total number of observations (images):** 5,856
- **Training observations:** 4,192 (1,082 normal cases, 3,110 lung opacity cases)
- **Validation observations:** 1,040 (267 normal cases, 773 lung opacity cases)
- **Testing observations:** 624 (234 normal cases, 390 lung opacity cases)


# Abstract
The diagnosis of the disease need lot of analysis and the doctor has to check all the insights 
of the x-ray image. The x-ray image will be taken by the scanner with ultra sound. The 
generated x-ray images are different that are compared with the normal images. In order to 
obtain the insights in a more accurate in less time lot of research is going on medical 
records. An in-depth exploration of the 'Chest X-Ray Images (Pneumonia)' dataset, an 
adapted version from Paul Mooney's collection. The dataset comprises radiological images 
with distinct categorizations into 'normal' and 'lung opacity' cases, indicative of the 
presence or absence of pneumonia. The dataset distribution reveals a total of 5,856 
observations, split into training, validation, and testing subsets. The deep learning methods 
are easily used so that the patterns from the x-rays will be easily scanned by the neural 
network algorithm then only the doctor will survive the patient from the disease. We 
proposed classification between the normal cases and the lung opacity cases. The CNN 
architecture of VGG-16 along with ResNet contains different layers will have the total 
parameters will be used it as the trainable parameters and in our architecture there is no 
non trainable parameters. The hyper parameter tuning will increase the results to more than 
95%. To classify the diseases we have taken the machine learning library keras. The base 
model will be developed using the transfer learning and the custom deep convolution neural 
networks. The Adam Optimizer is to reduce the connections between the layers to improve 
the accuracy in order to produce the best results. The categorical cross entropy is the loss 
function is used to test the trained model with the different set of images whether it is 
classify the disease correctly or not. So our model provides the accuracy to classify the xray images as normal or the lung opacity disease. The automatic classification of the 
medical x-rays will be done effectively then there is a chance of the low death rates because 
the patients will get the treatment in time

# Models:
-VGG16
-VGG19
-DENSENET169
-INCEPTIONV3
-XCEPTION


