# Masters-Degree---Thesis

# Project Title : 
Alzheimer Disease Detection and Prognosis from Clinical Data using Machine Learning Techniques 

# Data Used : 
The dataset name is "TADPOLE" which is downloadable from ADNI website https://ida.loni.usc.edu/login.jsp?project=ADNI## 

# Abstract : 
Alzheimer’s disease is the fifth most leading cause of death as per WHO impacting millions globally, 131 million cases projected in 2050. No cure has been found for
Alzheimer’s disease implying early diagnosing of Alzheimer’s stages Normal Cognition (NC), Mild Cognitive Impairment (MCI), and Alzheimer disease (AD) in
patients is cost-effective, reduce suffering among the community. In this thesis, Machine learning algorithms like ElasticNET, Gradient Boosting, Deep Neural Net, Support Vector Machines, and LSTM networks are used for the prediction of continuous cognitive variables MMSE, ADAS13, Ventricle and categorical classification of 3 AD stages. These predictions are performed on ADNI Clinical data. The evaluation metrics proposed are R2 , RMSE, Accuracy, Precision, Recall, F1-score. Gradient boosted regressor is a robust model compared to other algorithms achieving R2 of 90% and lowest RMSE scores. Dynamic LSTM obtained an accuracy of 78% outperforming other classifiers showing promising results by detecting  Alzheimer patients empowering medical supervisors to initiate appropriate treatment.

# Research question : 
1) Prediction of clinically important continuous variables namely the MiniMental State Examination (MMSE), Alzheimer Disease Assessment scale
(ADAS13) and Head sized normalised ventricle volume (Ventricles_Norm)- Regression task
2) Final prediction to classify the patient accurately as Healthy NC (Normal cognition), MCI (Mild cognitive impairment) and AD (Alzheimer Disease) by including new input predicted variables MMSE, ADAS13 and Ventricles_Norm from above - Classification task

# Results: 
## [A] Clasification Models (classify 3 stages NC/MCI/AD) with their Train Accuracy and Validation Accuracy respectively are depicted below
1) Dynamic LSTM 98% , 78%
2) Neural Net Classifier 97% , 67%
3) Gradient Boosting Classifier 84% , 73%
4) Support Vector Classifier:  75% ,  61%
## [B] Regression Models for prediction of Clinical cognitive assessment metrics like ADAS13, Ventricles_Norm, and MMSE scores of an Alzheimer patient with their Test R2 values 
1) Gradient Boosting Regressor = ADAS13: 90%  , Ventricles_Norm: 97%  and MMSE: 79% 
2) Elastic Net Regressor = ADAS13: 68%  , Ventricles_Norm: 83%  and MMSE: 58% 
3) Baseline Regressor = ADAS13: 38%  , Ventricles_Norm: 94%  and MMSE: 25%



