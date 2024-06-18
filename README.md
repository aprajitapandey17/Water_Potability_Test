# Comprehensive Water Quality Assessment and Potability Prediction using Multi-parameter Analysis
The objective of this machine learning problem is to predict whether a given set of water quality parameters meets the potability criteria or not based on the provided features.
# Data Dictionary
pH - Represents the pH level of the water.
Unit: pH (dimensionless)
Hardness - Indicates the concentration of minerals, primarily calcium and magnesium, in the water.
Unit: mg/L (milligrams per liter)
Solids - Refers to the total dissolved solids in the water, which includes minerals, salts, and organic matter.
Unit: ppm (parts per million)
Chloramines - Represents the concentration of chloramines, which are disinfection byproducts formed when chlorine is used for water treatment.
Unit: ppm (parts per million)
Sulfate - Indicates the concentration of sulfate ions in the water.
Unit: mg/L (milligrams per liter)
Conductivity - Reflects the water's ability to conduct an electrical current, which is influenced by dissolved ions.
Unit: µS/cm (micro Siemens per centimeter)
Organic carbon - Indicates the concentration of organic carbon compounds in the water.
Unit: ppm (parts per million)
Trihalomethanes - Represents the concentration of trihalomethanes, which are disinfection byproducts formed during water treatment.
Unit: µg/L (micrograms per liter)
Turbidity - Refers to the cloudiness or haziness of a fluid caused by large numbers of individual particles.
Unit: NTU (Nephelometric Turbidity Units)
Potability (Target Variable) - Indicates whether the water is considered safe for drinking or not.
Values: 0 (Not Potable), 1 (Potable)
# Data Structure 
No_of_columns – 10 Nos
No_of_Rows – 3277 Nos
# Conclusion 
The metrics used for the calculation of Accuracy is F1 - Score.
The model is moving towards overfitting as we are increasing the complexity of the data.
When SMOTE used for class imbalance has resulted in Overfitting .
Logistic Regression has giving the accurate result with very lesser difference between the F1 score of the training and the validation set , however overall performance of the model is underfitting


