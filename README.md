In this project, we leverage advanced ML and AI techniques, specifically Multi-Layer Perceptron
(MLP), Random Forest (RF), Support Vector Machine (SVM), and XGBoost algorithms, to
enhance the diagnostic process for pediatric appendicitis. 
The dataset used in this study was acquired in a retrospective study from a cohort of pediatric
patients admitted with abdominal pain to Children’s Hospital St. Hedwig in Regensburg,
Germany. Multiple abdominal B-mode ultrasound images were acquired for most patients, with
the number of views varying from 1 to 15.  The images depict various regions of interest, such as
the abdomen’s right lower quadrant, appendix, intestines, lymph nodes, and reproductive organs.

The dataset used in this study had missing data, outliers, and a large set of features. We addressed these issues by employing
techniques such as RandomForest and KNNImputer for handling missing and outlier data.
Additionally, we utilized feature selection methods, including Gain Ratio and wrapper methods
like Recursive Feature Elimination (RFE) and Random Forest, to improve model performance.
The results demonstrated that our models, specifically Random Forest and XGBoost, achieve
significant improvements in diagnostic accuracy. This suggests that our approach can potentially
reduce the incidence of unnecessary surgeries and improve patient outcomes by providing more
accurate and timely diagnoses.
