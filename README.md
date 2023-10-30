# Heart Diseases Diagnosis Using Artificial Intelligence Research Project

## Background
Heart diseases are widespread ailments affected by many factors. This project utilizes artificial intelligence and machine learning algorithms to diagnose heart diseases at an early stage. The dataset includes information from 303 participants, including their age, sex, serum cholesterol levels in mg/dL, chest pain type, resting blood pressure, and more.

## Research Questions
### Unsupervised Question:
- What are some structures of the max heart rate data that we have?

### Supervised Question:
- How is age related to the amount of cholesterol?

## Methods
In this research project, I employed various methods and materials to investigate the research questions, including:
- Data visualization using scatterplots, countplots, and histograms
- Exploratory data analysis with methods like describe, head, and groupby
- Data preprocessing techniques such as normalization, standardization, log transformation, and handling outliers
- Machine learning algorithms: Linear Regression, Logistic Regression, Naive Bayes, and K-means clustering

## Results
### Figure 1: Prediction of Cholesterol Levels by Age
![Cholesterol Prediction](figures/cholesterol_prediction.png) 
Figure 1 displays the prediction of cholesterol levels in blood using age as a feature. It reveals a weak correlation between age and cholesterol levels, as evidenced by the model's relatively high error rate.

### Figure 2: Heart Disease Distribution by Chest Pain Types
![Chest Pain Distribution](figures/chest_pain_distribution.png)
Figure 2 compares the distribution of people with and without heart diseases for four different chest pain types. It suggests that individuals with typical angina are more likely to have heart disease.

### Figure 3: Resting Blood Pressure Comparison by Gender
![Blood Pressure by Gender](figures/blood_pressure_gender.png)
Figure 3 illustrates the comparison of resting blood pressure between males and females, showing that males typically have lower resting blood pressure.

## Conclusions
### Findings:
- The research indicates that factors like chest pain types and max heart rates achieved can help predict the presence of heart diseases.
- The number of people affected by heart disease increases with age in both men and women.

### Future Work:
- Future research should compare different risk factors to determine which one is most important in predicting heart disease.
- The long-term goal is to predict heart disease at an even earlier stage and identify individuals at higher risk.

## Acknowledgments
Special thanks to Dr. Anat Caspi and Mr. Lawrence Tanimoto for their invaluable guidance and support throughout this research project. I also acknowledge the funding provided by the University of Washington.