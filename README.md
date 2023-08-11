# XGBass-Multi-classification

###Crime Classification Project
This repository contains the data and codebase for classifying crime categories based on various features from the San Francisco Crime dataset.

#Dataset Description
The dataset consists of various features related to reported crimes:

Dates: Timestamp of the crime incident.
Category: The category of the crime (e.g., WARRANTS, OTHER OFFENSES, LARCENY/THEFT).
Descript: Detailed description of the crime incident.
DayOfWeek: The day of the week when the crime occurred.
PdDistrict: The police department district.
Resolution: The resolution/result of the crime report (e.g., ARREST, BOOKED).
Address: Approximate address or location of the crime incident.
X, Y: The longitude and latitude

#Goal
The primary goal of this project is to predict the Category of the crime based on other features, making it a multiclass classification problem.

#Implementation Overview
Data Pre-processing:

Conversion of Dates into datetime format .
Encoding of categorical variables like DayOfWeek and Resolution...

#Model Selection:

focus on the XGBoost classifier, which handles multiclass classification well.

#Evaluation:

The models are evaluated based on metrics like accuracy, precision, recall, and F1-score for each class but because of my computer capacity i was not able to perform this part.


#Dependencies

Python
pandas
scikit-learn
XGBoost

#Contribution
Contributions are welcome! Please submit a pull request or open an issue if you find any bugs or have suggestions.

This README provides a brief overview of the project.




