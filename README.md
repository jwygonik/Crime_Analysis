---
## **<h1 align="justify"> Crime_Analysis Summary**
---

<p align="justify"> Crime in a major city (Los Angeles) examining what factors may have a relationship with the crime rate in certain areas (public mental health programs, income, unemployment, demographics, police presence.) We strive to understand the factors closely related to the crime rate and see what needs to be focused on to reduce crime. <p>

---
## Description of the communication protocols
<p align="Justify"> Our team has been communicating via slack and setting up zoom meeting times to go over details and assign next  steps. <p>


## Description Of Our Source Of Data 
<p align="justify"> Our team was assigned with the argument that demographics influence crime. Is there a difference in crime rate and factors.
Arguments posed and supported in our project are the following. What environmental factors directly correlate with the number of crimes and factors? How do other demographics play into crime? Is there less crime in areas where there are more human services available?
Resources we have sourced for our supporting argument is data regarding arrest data, census data, Los Angeles Arrests, and Los Angeles Crimes. We have also compared this data to LAPD Police Stations, Mental Health Centers, and Mental Health Programs.

Our team's target data is male and female.
<p>

## Project API Example 
![RandomOverSampler Results](https://github.com/jwygonik/Crime_Analysis/blob/main/Images/API_EXAMPLE.png?raw=true)
Image Desc: We produced an API called that specfically for Los Angeles, CA. We have ensure our API is protected. 

## Arrest Data Cleaning  
![RandomOverSampler Results](https://github.com/jwygonik/Crime_Analysis/blob/main/Images/ML_RDME.png?raw=true)
Image Desc: We have started the ML journey with cleaned data and added information. 

## Main Data Sets (Big Data) for reference:

Link 01: [LA_City_Arrest Data 2020](https://data.lacity.org/Public-Safety/Arrest-Data-from-2020-to-Present/amvf-fr72)

Link 02: [Mental Health Centers](https://geohub.lacity.org/datasets/lacounty::mental-health-centers/explore?location=33.800844%2C-118.295000%2C9.23&showTable=true)

Link 03: [Sheriff and Police Stations](https://geohub.lacity.org/datasets/lacounty::sheriff-and-police-stations/about)

Link 04: [Map - Individual Communties of the City of Los Angeles](https://www.laalmanac.com/LA/lamap2.php)

## Other References

Link 01: [LA Crime Data Set](https://www.kaggle.com/datasets/stefanoskypritidis/los-angeles-crimes-201019-cleaned-datased)

We have also designated resources to organize Los Angeles census data for 2020.

## Power Point 
Link: 01 [Power Point](https://docs.google.com/presentation/d/1WdwCFRmGpm31yviwYexSAIPkVO8Zu1uPUQ204DITov8/edit#slide=id.p)

## ERD La Crime Mental 
![RandomOverSampler Results](https://github.com/jwygonik/Crime_Analysis/blob/main/Images/ERD-LA_CRIME_MENTAL.png?raw=true)


## Update August 13th 2022 

##  Dashboard information for readme
<p align="Justify"> Include the storyboard image, Desp of tools: we are utilizing tableau public and python for a summary table for more information to help our audience grasp the objective of this project. We are putting our variables together. Our goal is to understand crime and the number of variables associated. We will have a center to join our programs to understand the data better. With zip codes, we will keep them as strings as they have integrators that can cause issues with our data. Our team concluded that unless data has a value in some measurement, we will keep it as a string. We had issues with our zipcodes as they are categorical and not a measure of data. Thus, using this data cleaning measure, we could simplify our data to a general audience; our goal is to use this data to find crime and human resources trends. <p>

## Description of interactive elements

<p align="Justify"> We have elected to utilize the filter and highlight interactive features for our visualizations. We chose those elements to relay the pertinent information of our research. <p>

##  Prepping/Setting Up DataBase

<p align="Justify"> We started by combining the arrest data and LAPD data on pandas. Cleaned the Mental Health Programs, Mental Health Centers, and Substance Abuse Programs to have the same columns, including the new ones added.
Our team exported the three data frames to SQL tables.
We created a table that would house all the Mental Health Programs, Mental Health Centers, and Substance Abuse Programs.
Loaded all of the data from the other tables into the main table.
We did not have to do a join here since we made all the columns the same in the cleaning process; we just had to load the data into the table instead.
Exported the grouped data to a CSV to do some additional cleaning in python.
Exported the complete data into the AWS database so we all could access the same data.

We are also breaking down census data by zip to join this with our other data already in AWS. Once our team's project is finished, we can bin everything and load this into the Random Forest machine learning model. We also set up a Neural Network that may also try out, depending on our success with the Random Forest model. The goal will be to predict the number of crimes based on environmental factors. Our team's preliminary model was created using the arrest data, and our final machine learning model will mirror this but have a different target variable(number of crimes)/ other feature variables to consider.

![RandomOverSampler Results](https://github.com/jwygonik/Crime_Analysis/blob/main/Images/MLSnap.png?raw=true?raw=true)

Above is the current snapshot of the accuracy of our Random Forest Model, taking in factors that contribute to the number of crimes. Below is a list of elements and types of crimes impacting our machine learning model and outcomes ranked from the highest relationship to the number of crimes to the lowest. (edited) 

![ML SNAPSHOT](https://github.com/jwygonik/Crime_Analysis/blob/main/Images/MLSnap.png)

## Overcoming Obstinaces 

Our team has been overcoming repeated errors and understanding how to move forward and pivot from our original plan.
Sorting through the documentation for all the components and tools we needed. As well as the struggles of cleaning a 
large data set. We plan on taking our data and condensing it to be digested well by the general public. 

Simplifying our complex idea has been an ongoing task. As we are very familiar with our data. We have used outside 
sources to better understand areas to expand on for the general public. 

