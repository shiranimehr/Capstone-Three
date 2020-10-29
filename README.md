# COVID-19 Detection Based on Chest X-ray

Coronavirus disease 2019 (COVID-19) is a highly infectious disease that has affected almost every country in the world. Several tests have been developed to detect the disease at different stages. However, these tests can be slow and/or costly.

Unlike the specific tests that can be limited and costly, chest X-rays are relatively cheap and easy to obtain. Here we are investigating the idea of using chest X-rays as an alternative to the more advanced tests.   

We use a dataset from https://github.com/ieee8023/covid-chestxray-dataset which is a public open dataset of chest X-ray and CT images of patients which are positive or suspected of COVID-19 or other viral and bacterial pneumonias (MERS, SARS, and ARDS). This data has been collected from public sources as well as through indirect collection from hospitals and physicians. 

We utilize different convolutional neural network models based on MobileNet to classify X-ray images and compare their performance considering metrics such as accuracy, ROC and Precision-Recall curves. Our results show that accuracies close to 80% are achievable by using a CNN classifier. 
