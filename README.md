# Introduction

This project  **Insurance Policy Analysis** is designed to help Insurance Provider analyze factors inflencing insurance claims using data analysis techniques.

The report explores:
- Claim Amounts
- Insurance coverages
- Claim frequency

It purpose is to analyze  pattern in claim behavior, explore the impact of demographic and vehicles characteristics on claims and accesss the relationship between household income, education and insurance claims.

# Problem Statement 
Insurance providers struggle to identify patterns in claim behavior and the key factors contributing to higher claims. 

This project seeks to analyze policyholder, vehicle, and socioeconomic data to support better claims management and risk-based decision-making.

# Key Questions
The following questions  are used as guidlines to ensure effective and accurate analysis:
- How does claim frequency vary across different age group, gender and marital status?
- Is there a correlation between the level of education and the average claim amount?
- How does the type of coverage zone affect claim frequency?
- What is the relationship between household income levels and claim amounts or frequency?
- How does car use impact the average claim amount and frquency?
- Does having kids influence claim frequency or amount?
- Which car make has the highest and lowest average claim amount?
- How does the car's model year relate to claim amount and frequency?
- Are there any notable pattern in claims associated with different car colors?
- How does household income relate to the chosen coverage zone?

# Data Overview

This dataset contains **37,542** details of policy holder. It contains all neccessary informations of each one of them. It comprises of various roles which makes it easy for analysis. the roles includes:
- **ID** - Unique number assigned to each policyholder.
- **Birthdate** - Date the policyholder was born.
- **Age** - How old the policyholder is.
- **Marital status** - Whether the person is single, married, etc.
- **Car use** - How the car is used (private or commercial).
- **Gender** - The policyholder’s sex.
- **Kids-driving** - The number of kids in the household that drives.
- **Parent** - Indicates if the policyholder is a parent.
- **Education** - Highest education level attained.
- **Car make** - Brand of the car (for example, Toyota).
- **Car model** - Specific model of the car.
- **Car color** - Color of the car.
- **Car year** - Year the car was manufactured.
- **Claim frequency** - Year the car was manufactured.
- **Coverage zone** - Area where the policy is covered.
- **Claim amount** - Money paid or claimed for losses.
- **Household income** - Total income earned in the household.
- **Age group** - Age category the policyholder belongs to.

# Data Prepparation
To ensure accuracy, the dataset underwent series of **cleaning and transformation steps** before analysis. This process was taken to **PowerBI** focusingon recovering inconsistencies and preparing the data for visualization.

# Key steps taken
- Load the dataset into PowerQuery.
- Check for null values.
- Checked if all the columns are in the right datatype.

# Measures (DAX)
 **Descriptions**
 Contains calculated measures created using **DAX function** to define  key KPIs. These measures form key backbone of the dashboard, and provides insights suitable for the analysis.

 **Fields**
 - Dynamic Title
 - Claim to Income ratio
 - Total Household income
 - Total claim amount
 - Average household income
 - Average claim amount
   
 **Purpose:**
 This is to help insurance team underatand pattern in claim behavior, understand the impact of demographic and vehicles characteristics on claims and accesss the relationship between household income, education and insurance claims.

# Data Analysis and visualization

The dashboard is structured into three main pages.

## Page 1:

<img width="896" height="497" alt="Insurance Policy_1" src="https://github.com/user-attachments/assets/85620653-2707-4ba1-8ca1-4a0f4b2e9482" />

