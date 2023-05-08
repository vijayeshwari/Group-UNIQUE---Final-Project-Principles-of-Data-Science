# WINE QUALITY PREDICTION MODEL

**Goal:**

1) To the investigation of the significance of the characteristics for the assessment of wine quality. 

2) To utilize a neural network to enhance the performance of the prediction model. 

**Technologies Used:**

scikit-plot

pandas



**Procedure Followed:**

Unbalanced Data Visualize the quality class label in the red wine and white wine dataset as follows:

Red wine:
![image](https://user-images.githubusercontent.com/50485624/236934551-ba122c9b-272d-454e-afdc-12f8d4b9c4ea.png)

White wine:
![image](https://user-images.githubusercontent.com/50485624/236934817-cdda168b-175f-4488-90d4-f2082e248fab.png)

**Balancing the dataset using SMOTE technique**

Therefore, to solve the data imbalanced problem we used the SMOTE technique for red and white wine.

Red wine:

![image](https://user-images.githubusercontent.com/50485624/236935445-6bc50929-3afd-4ece-88ab-9b04af8245a6.png)
 
White wine:
![image](https://user-images.githubusercontent.com/50485624/236935470-4d57e349-0ebf-4471-b4fa-eb14d5400474.png)
 
**Feature Selection**

To understand and correlate features. Pearson coefficient correlation matrices evaluate feature correlation.

Red wine:
![image](https://user-images.githubusercontent.com/50485624/236935753-61424e67-7f6f-4c27-990c-58c666d881fd.png)
 
White wine:
![image](https://user-images.githubusercontent.com/50485624/236936050-3cd19067-9210-4b8a-b878-2fb33fa8b45c.png)
 
**Model and Evaluation:** 

We implemented the model using machine learning methods including SVM, NB, and ANN:

**SVM for Red wine and White wine**

SVM for red wine when kernal=rfb
![image](https://user-images.githubusercontent.com/50485624/236936617-3680f017-1227-4a42-a5d3-01aa4c6beb45.png)
 
SVM for white wine when kernal=rfb
![image](https://user-images.githubusercontent.com/50485624/236936661-773748d6-c64b-4d80-aa5e-55c6a0061806.png)

**Naive Bayes or NB for Red wine and white wine**

NB for red wine:
![image](https://user-images.githubusercontent.com/50485624/236937689-0e77bcb9-f993-4fc2-943d-ea72476b283f.png)

NB for white wine:
![image](https://user-images.githubusercontent.com/50485624/236937748-15ce26bf-8226-4573-8e1e-1c68ab22145f.png)

**ANN for Red wine and White wine**

ANN for red wine:
![image](https://user-images.githubusercontent.com/50485624/236937986-1dea7ee5-2484-436a-a453-2b9e8fe51546.png)

ANN for white wine:
![image](https://user-images.githubusercontent.com/50485624/236938022-99c873dd-49dc-45b5-9389-d34a756a1790.png)
 
 
**Comparing SVM, NB and ANN Results for red wine**
![image](https://user-images.githubusercontent.com/50485624/236938339-b19ba08b-7b2e-4fad-b221-fed4904e7418.png)

![image](https://user-images.githubusercontent.com/50485624/236938153-53cc91be-b4bc-46bb-b296-b8363fbcb140.png)

**Comparing SVM, NB and ANN Results for white wine**
![image](https://user-images.githubusercontent.com/50485624/236938408-be99a148-4acd-4415-96ac-02d3b1920c27.png)

![image](https://user-images.githubusercontent.com/50485624/236938207-7ef146d9-5fb5-4c9f-a818-3e19ec4c2923.png)

**Concusion**

The model's performance is enhanced after the sample datasets, which are balancing datasets, are applied. 
In general, the classification model performed better when unnecessary features from the datasets were removed.
On both the red and white wine datasets, we found that the artificial neural network (ANN) produced the greatest accuracy results among these three machine learning algorithms. 
As a result, picking the suitable features and balancing the data in the classification algorithms might enhance the performance of the prediction model.




