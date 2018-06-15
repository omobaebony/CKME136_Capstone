# CKME136_Capstone

Dataset
The dataset used for this study can be found at Fatality Analysis Reporting System (FARS) (2016) publicly released by National Highway Traffic Safety Administration (NHTSA). FARS is a nationwide census of fatal injuries in Motor Vehicles traffic crashes on U.S. public roads and contains variables that characterize person, vehicle and crash factors. 

These files contain elements derived from the FARS datasets to make it easier to extract certain data classifications and topical areas, such as commonly used age groups, speeding involved crashes, and distraction involved crashes. It represents different data points in the US Traffic fatality Records.

The specific dataset used for analysis in this project is formed by extracting key attributes from the raw data. There is an Accident (ACC_AUX), Vehicle (VEH_AUX), and Person (PER_AUX) level auxiliary file for each year of data.

Accident.csv contains the following fields:[2] 
1.	VE_TOTAL - # of vehicles involved in the crash 
2.	FUNC_SYS – Trafficway classification in which the crash occurred
3.	WEATHER1 – Atmospheric condition that existed at the time of the crash 
4.	LGT_COND – Type /level of light that existed at the time of crash 
5.	TYP_INT – Identifies and allows separation of various intersection types
6.	FATALS - # of people who died as a result of the crash 
7.	DRUNK_DR - # of alcohol influenced drivers involved in the crash 

Person.csv contains the following fields: :[2]  
1.	AGE - Driver’s age at the time of the crash 
2.	SEX - Identifies the sex of driver involved in the crash 


[2] Data Dictionaries used for this analysis is derived from the following:

Fatality Analysis Reporting System (FARS): Analytical User’s Manual 1975-2016 https://crashstats.nhtsa.dot.gov/Api/Public/Publication/812447 

Auxiliary Data Files
Users Guide: A set of auxiliary files has been created since 1982. These files contain elements derived from the FARS datasets to make it easier to extract certain data classifications and topical areas, such as commonly used age groups, speeding involved crashes, and distraction involved crashes. There is an Accident (ACC_AUX), Vehicle (VEH_AUX), and Person (PER_AUX) level auxiliary file for each year of data.
(2007-2016) https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812448 

Terms of Use
NHTSA/DOT terms of use: https://www.nhtsa.gov/about-nhtsa/terms-use

