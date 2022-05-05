# Heart-FailurePrediction

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.
Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

**BACKGROUND**

Heart failure is the state in which muscles in the heart wall get fade and enlarge, limiting heart pumping of blood. The ventricles of heart can get inflexible and do not fill properly between beats. With the passage of time heart fails in fulfilling the proper demand of blood in body and as a consequence person starts feeling difficulty in breathing.

The main reason behind heart failure include coronary heart disease, diabetes, high blood pressure and other diseases like HIV, alcohol abuse or cocaine, thyroid disorders, excess of vitamin E in body, radiation or chemotherapy, etc. As stated by WHO, Cardiovascular Heart Disease (CHD) is now top reason causing 31% of deaths globally. India is also included in the list of countries where prevalence of CHD is increasing significantly.

In addition to relative scarcity of studies focusing on heart failure, the present study has specific importance in the Indian context, as diet patterns in India are different with other the countries.

The main objective of this study is to estimate death rates due to heart failure and to investigate its link with some major risk factors.

**DESIGN**

The project is designed in a way where I have tried to use multiple classification models to predict heart failure as accurately as possible. The dataset has 13 columns which are as follows:

1.  	Age (Float, Discrete) 
2.  	Anaemia (Binary)
3.  	Creatinine_phosphokinase (Continous)
4.  	Diabetes (Binary)
5.  	Ejection_fraction (Discrete)
6.  	High_blood_pressure (Binary)
7.  	Platelets (Float, Discrete)
8.  	Serum creatinine (Continous)
9.  	Seum_sodium (Discrete)
10.  	Sex (Binary)
11.  	Smoking (Binary)
12.  	Time (Discrete)
13.  	Death_ Event (Binary

We can use the first 12 columns as Independent Variables (IV) and the last column, Death_ Event, as the Dependent Variable (DV) as we are trying to estimate that feature. As Death_Event, which is out Dependent Variable, is a Binary column, this case is a Binary Classification problem.

A detailed working and summary can be found in the PDF uploaded where you'll find my approach, the working and the interpretation of results and a conclusion.
