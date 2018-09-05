# Personalized Cancer Diagnosis
## Description
A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). As not all mutations lead to cancer.
Due to a mutation in a gene, there is some genetic variation developed in a gene. But the question comes, from which particular mutation this genetic variation happened in a gene. Currently this interpretation of genetic mutations is being done manually which is a very time-consuming task. Based on a gene and a variation in it, a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

## Business Problem
### The workflow is as follows:
1. A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze.
2. The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest.
3. Finally, this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them into any one of the 9 different classes.
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.

#### Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.

## Problem Statement
Classify the given genetic variations/mutations based on evidence from text-based clinical literature. In this problem, we need to find the mutation-type given the gene, variation and some text data from published research.

## Source of Data
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
Data: Memorial Sloan Kettering Cancer Center (MSKCC)

## Real-world/Business objectives and constraints.
No low-latency requirement.
Interpretability is important.
Errors can be very costly.
Probability of a data-point belonging to each class is needed.

## Getting Started
Start by downloading the project and run " Personalized-Cancer-Diagnosis.ipynb" file in ipython-notebook.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy and scipy.
3. mlxtend

## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/
3. mlxtend: pip install mlxtend

## Running the tests
This project can be tested in real-world with similar data. The shape of the test data should be same as of training data. In order to test the project in real world, perform following steps in order:
1. Run the project just before "Base Line Models"
2. Once the project ran completely, add your testing data to the project at "Reading Data" section.
3. Perform data pre-processing and data cleaning.
4. Out of total 8 models choose any one model as per your choice and run that model.
5. Using best hyper-parameter of that model, run that model on your test data.
6. Note down the results.
7. For more results you can try with another model and follow the same procedure.

## Built With
•	ipython-notebook - Python Text Editor

•	sklearn - Machine learning library

•	seaborn, matplotlib.pyplot, - Visualization libraries

•	numpy, scipy- number python library

•	pandas - data handling library

•	mlxtend - used for stacking the models

## Authors
•	Gaurav Sharma - Complete work  

## Acknowledgments
•	Applied AI Course
