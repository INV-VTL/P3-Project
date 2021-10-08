![2](C:\Users\rychu\Desktop\FLT\P3M\P3-Project\Images\2.jpg)

# Terry Traffic Stops Analysis

## Overview

This project analyzes a data set containing information on traffic stops made based on the notion of "reasonable suspicion" in order to create statistical models which accurately predict whether an arrest was made after a "Terry Stop."

## Data Used

The data set used in this project was pulled from data.gov and it represents records of police reported stops under the Terry v. Ohio landmark Supreme Court case in 1967.  The data set contains various features of each traffic stop made such as stop resolution, officer gender, perceived subject race, time of report, etc.

## Methods

This project uses descriptive analysis and statistical modeling in order to predict the outcome of a traffic stop based on the features provided in the Terry Stop data set.  Several classifier models were created including a Logistic Regression model, KNN model,  Decision Tree model, and Gradient Boosting model.  The most accurate model was then run through Grid Search CV in order to further tune the models accuracy.

## Conclusions

With the provided data, the most accurate model which was selected to run through grid search was the Decision Tree model.

## Repository Structure

- images
- .gitignore
- P3 Notebook.ipynb
- P3 Notebook PDF
- P3 Presentation PDF
- Presentation pptx
- README
- Terry_Stops.csv