# Cancer-Histology-Project

## Dataset:
The project focuses on classifying cancerous tissues into one of eight distinct groups. The dataset comprises 5,000 images of tissues with cancerous tumors, each categorized into one of these eight groups. The objective is to develop an effective machine learning algorithm that accurately assigns the images to their correct categories.

## Methods and Experimentation:
To accomplish this goal, the project explores a range of methods and conducts nine distinct experiments:

#### Dimensionality Reduction Methods:
such as PCA or tSNE.
#### Classification Methods:
such as SVM, CNN or Random Forest Classifier.

## Hyperparameters:
For each of the nine experiments, specific hyperparameters are selected, including kernel choices for SVM, layer architectures for CNN, and the number of trees in the Random Forest Classifier. These parameters are chosen systematically to explore the model's performance across various settings.

## Comparative Analysis:
The project involves a comprehensive comparative analysis of the results obtained from each of the nine experiments. The primary metrics considered for comparison include training and test accuracy to assess potential overfitting. Additionally, confusion matrices are generated to evaluate the models' performance on the test data. Furthermore, tSNE is used to visualize the test data in two dimensions, aiding in understanding how well the models separate different tissue types.

## Data Preparation and Additional Resources:
A link to the dataset:  https://zenodo.org/record/53169#.Yo3WLS8RqUn. Additionally, a link to a short article explaining the data preparation process, details about the various tissue types, and an overview of the methods attempted for classification:  https://www.nature.com/articles/srep27988. This resource offers valuable insights into the dataset and its complexities.

## Project Objective:
The primary objective of this project is to create a machine learning algorithm capable of processing 150x150x3 pixel images and accurately assigning them to one of eight distinct cancerous tissue categories. This involves careful selection of dimensionality reduction techniques and classification algorithms, with the ultimate aim of achieving high accuracy in categorization.


*This project is my final project in the Machine Learning course as part of my Bachelor's degree in Digital Medical Technologies.

<img width="549" alt="image" src="https://github.com/Noamko128/Cancer-Histology-Project/assets/131696249/a1e96de3-7fd5-41f8-9dbb-4ee5666fcf3e">
