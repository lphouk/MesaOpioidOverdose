# MesaOpioidOverdose

Author: Leo Phouksouvath
Date: 7/17/23

## Overview

This repository contains the code and analysis for an observational study on opioid overdoses in Mesa, Arizona. The study uses data taken from the Medical Opioid Overdose Incidents record, covering a total of 6,832 incidents recorded from May 2018 to March 2023. The goal of the study is to identify factors associated with fatal opioid overdoses in the region.
Data Source

The data used in this study was obtained from the Medical Opioid Overdose Incidents record, a comprehensive database maintained by the City of Mesa, Arizona. It includes detailed information about each incident, such as date, patient characteristics (age, gender), treatment administered (including naloxone), and the final outcome (fatal or non-fatal).
Findings

Based on the analysis of the dataset, the study found that more than half of the opioid overdose fatalities in Mesa, Arizona, were observed to be from elderly individuals, representing 52.2% of the fatalities. Males constituted a larger proportion of the fatalities, but statistical tests determined that the differences in proportions of deaths between genders were statistically insignificant.
Statistical Model

A logistic regression model was used to predict the log odds of an adult dying from an opioid overdose in Mesa, Arizona. The model identified age and the use of naloxone as the most statistically significant predictors of a fatal overdose. The findings suggest that age and naloxone administration play crucial roles in determining the outcome of an opioid overdose incident.
Implementation Details

The entire study and analysis were conducted using the R programming language. The code is available in the "FinalProject-Phouksouvath.Rmd" file, which is a markdown file containing all the code and analysis for the project. By knitting this file, a PDF document of the full report is generated.
Reproducibility

To reproduce the study's results, ensure you have the necessary R packages installed as specified in the Rmd file. Simply run the code in the Rmd file, and it will perform the data analysis, create visualizations, and generate the final report in PDF format.
Additional Notes

This study focuses specifically on opioid overdoses in Mesa, Arizona, and the findings may not be generalizable to other regions. Moreover, the dataset might have limitations, and it's essential to interpret the results with consideration of any potential biases or confounding factors.
Contact Information

For any inquiries or further information about this study, please feel free to contact:

    Name: Leo Phouksouvath
    Email: lphouks@gmail.com

License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code as long as you give appropriate credit and include the license notice in any derivative works.
