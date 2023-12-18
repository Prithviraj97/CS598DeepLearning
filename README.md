# Learning with limited Data
Contains all the code and Term project paper for the Deep Learning class. For this project, I did image classification on four datasets that have small sample sizes, i.e. CIFAR-10, CIFAR-100, Fashion-MNIST, and MNIST. The objective of the project was to find the best deep-learning model for image classification tasks. 
Codes were implemented with the help of resources like towardsdatascience.com, medium.com, and papers with code. 

We experimented with the use of small datasets like CIFAR-10, CIFAR-100, MNIST, and FMNIST on image classification tasks using some conventional deep-learning techniques for image classification.  We experimented using CNN, Compact Convolutional Transformers (CCT), and Vision Transformers (ViT) and compared their efficiency and performance. 
# Abstract of the paper: 
The rise of powerful Neural Networks has also created a need for significantly large datasets to train and validate the model. Many large corporations have spent hundreds of millions in data collection rather than working a way around developing an algorithm to work with a small dataset. While some data are easy to collect, many real-world problems have very little data available, medical imaging, and tumor detection being one of them. In this paper, we explore how different Deep Learning tools can be used on problems that have a comparatively limited data set. Here we have discussed and examined the use and efficiency of different Neural Networks on image classification problems with small data sets. For this paper, we are focused on image classification problems with a small training size. We explore the use of Conventional neural networks like CNN, and modified techniques like Transformers Compact Convolutional Transformer (CCT) and Vision Transformer (ViT) to solve an image classification problem. The CCT gives an accuracy of ~98\% on all of the four datasets. Transfer Learning and Data augmentation techniques used on the CIFAR-10 and CIFAR-100 dataset also gives better result in comparison to the regular dataset. Our objective is to find a Neural Network that can work on problems with limited data producing as little error as possible.  
# Methodology
To explore different models being used for learning with limited samples, we will run all the models (CNN, CCT, ViT) on different datasets and compare their efficiency. We also use the Data Augmentation and Transfer Learning techniques on a few of the datasets to see whether CNN's efficiency can be increased on datasets where it performs poorly. Conventional CNN performs remarkably well when applied to MNIST and Fashion-MNIST datasets. Compact Convolutional Transformer outperforms CNN in all of the datasets we have examined. CCT can make remarkable breakthroughs in the field of computer vision and NLP tasks. Proper dissection of CCT on NLP tasks is yet to be done, but we believe that CCT can perform with optimal accuracy on any NLP task. In this paper, we will focus on the use of CCT, CNN as the modern state of art architecture for image classification problems.
To optimize the CNN model performance on the CIFAR-10/100 datasets, we have applied data augmentation techniques on both of the datasets. Transfer Learning has also shown some improvement in the use of CNN on CIFAR datasets. It is important to mention that using a dropout layer can also somewhat increase the validation accuracy of CNN by nearly 4\%. Transfer Learning, Data Augmentation, and Cosine loss function are three of the widely used techniques to deal with small datasets. For our experiment, we have only focused on data augmentation and transfer learning. The cosine loss function can increase accuracy by almost 30\% when used in place of cross-entropy loss.

![cctcifar10](https://github.com/Prithviraj97/CS598DeepLearning/assets/60533093/e8f7b19d-4191-4c60-be4a-4bff108c5c5d)
![CCTCIFAR100AC](https://github.com/Prithviraj97/CS598DeepLearning/assets/60533093/fab612b4-e9b3-42a6-939d-6486291de8eb)
