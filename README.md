# Diabetes-Health-Indicators-Prediction
This model focuses on predicting whether a patient of hospital is diabete. The model centers on analyzing data features, transforming and balancing data, and predicting outcomes using purely statistical models as  Random Forest, XG Boost,...

There are 3 datasets in .zip file:

1."diabetes _ 012 _ health _ indicators _ BRFSS2015.csv": is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is class imbalance in this dataset. This dataset has 21 feature variables

2."diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv": is a clean dataset of 70,692 survey responses to the CDC's BRFSS2015. It has an equal 50-50 split of respondents with no diabetes and with either prediabetes or diabetes. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is balanced.

3."diabetes _ binary _ health _ indicators _ BRFSS2015.csv": is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.

In project, i train and i predict the 3rd dataset, the imbalanced. This is more dificult and complex than other
