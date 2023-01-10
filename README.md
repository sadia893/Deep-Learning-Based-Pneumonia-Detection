# Deep-Learning-Based-Pneumonia-Detection
CNN,Resnet50,VGG16,InceptionNet 
The application of machine learning and artificial
intelligence in medicine is expanding. This is especially true for
medical fields that use a lot of biological images and where the
gathering and processing of a lot of digital images is necessary
for the diagnostic processes. The analysis of medical images
using machine learning increases the consistency and accuracy
of reporting. This study reviews the use of machine learning
algorithms to analyze chest radiographs to improve decision-
making and reach the correct diagnosis. This work mainly
focuses on developing processing models using deep learning
techniques based on convolutional neural networks such as **CNN
VGG16, ResNet-50, and InceptionNet**. These models aim to
help with the classification problem of determining whether
there are pneumonia-related abnormalities in the chest x-ray
and classifying his x-rays into two categories according to the
detection results. increase.

We have chosen a dataset which is provided by Guangzhou
Women and Children’s Medical Center, Guangzhou for this
project which is available in Kaggle1 .This dataset consists of
5856 chest X-ray images in JPEG format that are organized
into three folders: train, test, and val. Each of these files
has two subfolders that each include pictures of pneumonia
affected or healthy people.Before being eliminated from the analysis of the chest x-ray
images, each chest radiograph was first examined for quality
control. The photographs were graded by two qualified doctors
prior to the diagnosis being utilized to train the AI system. As
a result, the images are of a high caliber and come in various
sizes. 

Dataset Detail
         Train   Test  Validation
Normal    1299    234   50
Pneumonia 3833    390   50
