# Spark_workshop_7.7.20
This pakage incduing one dataset, three notebooks and one slide that used in the workshop.
I
nformation about the data and the problem we are going to predict:
LOGISTIC REGRESSION - HEART DISEASE PREDICTION

* Introduction
World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression

* Data
The dataset is download from Kaggle website:https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression/data. It is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

* Project goal:to predict whether the patient has 10-year risk of future coronary heart disease (CHD).

* Variables
Demographic:
• Sex: male or female(Nominal)
• Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
Behavioral
• Current Smoker: whether or not the patient is a current smoker (Nominal)
• Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
Medical( history)
• BP Meds: whether or not the patient was on blood pressure medication (Nominal)
• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
• Diabetes: whether or not the patient had diabetes (Nominal)
Medical(current)
• Tot Chol: total cholesterol level (Continuous)
• Sys BP: systolic blood pressure (Continuous)
• Dia BP: diastolic blood pressure (Continuous)
• BMI: Body Mass Index (Continuous)
• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
• Glucose: glucose level (Continuous)
Predict variable (desired target)
• 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)
