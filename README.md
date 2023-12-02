# Lung Cancer Disparities

## Introduction

Although cancer is a disease that affects people of all backgrouds across the United States, certain racial and ethnic groups are effected by it more severly than others. For example, According to studies done by the National Cancer Institute's [Surveillance, Epidemiology, and End Results Program](https://seer.cancer.gov/), Black/African American people had higher death rates than all other racial/ethnic groups for most cancer types. The same study also found that Hispanic and African American women had disproportionately higher rates of cervical cancer than women of other racial/ethnic groups. 

Motivated by such alarming disparaties in health, we have decided to use the power of data science to help provide a solution to this problem by first identifying the most vulnerable people among racial and ethnic minorities. Then, we will be able to predict vulnerable people so that they can seek preventative care as early as possible.

## Research Questions

Our research aims to (1) investigate whether there is a significant association between demographic data such as race, gender and the risk factors for developing lung cancer and (2) to determine whether machine learning can be used to predict and prevent the onset of lung cancer in vulnerable populations.

Using regression and classification analysis, the research will develop predictive models that can identify vulnerable populations and recommend preventative care among risk groups. Exploratory data analysis will be conducted to examine the relationships between race, gender, and other demographic variables, and cancer risk factors such as smoking, and alcohol consumption. 

## Data

To conduct our research project, we have collected clinical data from a sample of 2000 lung cancer patients out of a larger 12,139 patient set from the [National Cancer Institute GDC Data Portal](https://portal.gdc.cancer.gov/). When downloaded, the data is a json file that contains data objects representing each patient. For each patient, four categories of information exist. One is their case id, followed by their diagnostic, demographic, as well as follow up information. 

Like most data from other areas of research, our data set included either missing, incomplete, or redundant data. For example, not all patients had a value entered for each attribute and other times, some patients did not have the same attributes at all. For that reason the data set needed extensive amounts of cleaning.


