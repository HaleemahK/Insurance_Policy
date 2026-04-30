# Introduction

This project  **Insurance Policy Analysis** is designed to help Insurance Provider analyze factors inflencing insurance claims using data analysis techniques.

The report explores:
- Claim Amounts
- Insurance coverages
- Claim frequency

It purpose is to analyze  pattern in claim behavior, explore the impact of demographic and vehicles characteristics on claims and access the relationship between household income, education and insurance claims.

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

## Page 1: Claim Frequency by demographics, car make and coverage zone

**Insurance Goal**
Analyze the claim frequency by demographics(gender,age group, marital status), the average claim amount by car make and the household income, claim amount by coverage zone.

<img width="893" height="507" alt="Insurance Policy_1" src="https://github.com/user-attachments/assets/2471cb85-7ced-45ea-a5f7-b6bb206ba3b8" />

# Key Metrics (Top of the page): Total household income, Total claim amount, Average household income, Average claim amount and Claim to Income ratio.

- **Dynamic Title:** This helps the title to change automatically based on the fliter applied.
- **Total household income:** This represents the sum of all incomes from all households.
- **Total claim amount:** This represents the total money paid out for all insurance claims.
- **Average household income:** The typical income per household (total income divided by number of households).
- **Average claim amount:** This represents the average money paid per claim.
- **Claim to Income ratio:** This shows how large claims are compared to income (claim amount relative to income).

These KPIs helps the Insurance management team improve risk assessment, pricing, customer targeting, and profitability control.  

------

## Visuals

- **Claim Amt by Gender (Donut chart):** It represents which gender makes more claims and their share of total claims.
- **Claim Amt by Age group (Clustered column chart):** It Compares claim amounts across different age groups.
- **Claim Amt by Marital status (Clustered column chart):** It shows how claim amounts differ between single, married etc.
- **Avg claim amt by Car make (Clustered column chart):** It shows which car brands (e.g., Toyota, Honda) have higher or lower average claim costs. 
- **Household income and claim amount by coverage zone (Clustered bar chart):** It compares income and claim amounts across different locations to see where risk or payouts are higher.

## Slicers: Year and Car

The dashboard includes **Year,Car** slicer that allows user to fliter and interact with the data.

This interactive fliters ensures that KPIs,charts and visuals adapt instantly giving the Insurance team a flexible view by narrowing the focus on specific car or year.

------

# Page Two: Effect of claim amounts on Car use, Kids driving, Education, Car year, Car color.

****Insurance Goal**
Analyze the effect of claim amounts on Car use, Kids driving, Education, Car year, Car color.

<img width="898" height="506" alt="Insurance Policy_2" src="https://github.com/user-attachments/assets/b9df4c8a-cf06-4372-bb06-1588bc78c64f" />


# Key Metrics (Top of the page): Total household income, Total claim amount, Average household income, Average claim amount and Claim to Income ratio.

- **Dynamic Title:** This helps the title to change automatically based on the fliter applied.
- **Total household income:** This represents the sum of all incomes from all households.
- **Total claim amount:** This represents the total money paid out for all insurance claims.
- **Average household income:** The typical income per household (total income divided by number of households).
- **Average claim amount:** This represents the average money paid per claim.
- **Claim to Income ratio:** This shows how large claims are compared to income (claim amount relative to income).

These KPIs helps the Insurance management team improve risk assessment, pricing, customer targeting, and profitability control.  

------

## Visuals

- **Claim Amt by Car use (Pie chart):** It represents the claim amount between private and commercial car use.
- **Claim Amt by Kids driving (Clustered column chart):** It compares claims for households with kids who drive vs those without.
- **Claim Amt by Education (Clustered column chart):** It shows how claim amounts differ across education levels.
- **Claim Amt by Car year (Line chart):** It shows how claims change based on how old or new the car is.
- **Claim Amt by Car color (Clustered column chart):** It represents top 10 claim amounts across different car colors.

## Slicers: Year and Car

The dashboard includes **Year,Car** slicer that allows user to fliter and interact with the data.

This interactive fliters ensures that KPIs,charts and visuals adapt instantly giving the Insurance team a flexible view by narrowing the focus on specific car or year.

------

# Page Three: Effect of claim amounts and claim frequency on Car make, Household income by coverage zone.

****Insurance Goal**
Analyze the effect of claim amounts and claim frequency on Car make, Household income by coverage zone.

<img width="897" height="505" alt="Insurance Policy_3" src="https://github.com/user-attachments/assets/495debed-0ece-45ca-93a5-64dd8bd883b3" />

# Key Metrics (Top of the page): Total household income, Total claim amount, Average household income, Average claim amount and Claim to Income ratio.

- **Dynamic Title:** This helps the title to change automatically based on the fliter applied.
- **Total household income:** This represents the sum of all incomes from all households.
- **Total claim amount:** This represents the total money paid out for all insurance claims.
- **Average household income:** The typical income per household (total income divided by number of households).
- **Average claim amount:** This represents the average money paid per claim.
- **Claim to Income ratio:** This shows how large claims are compared to income (claim amount relative to income).

These KPIs helps the Insurance management team improve risk assessment, pricing, customer targeting, and profitability control.  

------

## Visuals

- **Claim amount by claim frquency (Clustered column chart):** It represents how total claim amount changes with the number of claims made.
- **Claim amount by car make (Clustered column chart):** It compares total claim amounts across car brands (e.g., Toyota, Ford).
- **Household income by coverage zone (Clustered bar chart):** It represents how total income differs across regions.
- **Avg household income by coverage zone (Clustered bar chart):** It represents the typical income level in each regions.

## Slicers: Year and Car

The dashboard includes **Year,Car** slicer that allows user to fliter and interact with the data.

These interactive fliters ensures that KPIs,charts and visuals adapt instantly giving the Insurance team a flexible view by narrowing the focus on specific car or year.  

# Key Analysis Findings

The analysis provided various insights into claim behavior, impact of demographic and vehicles characteristics on claims and access the relationship between household income, education and insurance claims.

Here are various Finding:

- **Total Household income-** *$5.53bn*
- **Total claim amount-** *$1.88bn*
- **Average Household income-** *$147.25K*
- **Average claim amount-** *$50.03K*
- **Claim to income ratio-** *0.34*
- The male gender has higherclaim amountcompared to the female with *50.08%*.
- The **middle aged** group has the highest claim amount of *$532.76M* while the **elderly** has the lowest with *356.25M*.
- **Singles** have the highest claims *$774.8M*, **Married** people are next *$832M* while divorced and separated are much lower.
- **Hilman** has highest average claims *$79K* compared to which are slightly lower ($62K–$53K range).
- Urban and highly rural areas have the highest income and claim amounts while Suburban and rural areas are slightly lower but similar.
- **Private** cars dominate claims *80.08%*, **Commercial** cars contribute only *19.92%*.
- Households with *0 kids* driving have the highest claims *$1.34bn*, claims drop sharply as number of kids increases:
     - 1 kid: *$338.62M*
     - 2 kids: *$163.58M*
     - 3 kids: *$40.87M*
- **Bachelors degree** holders have the highest claims *$940.2M*, followed by High School *$518M*, Masters *$283.09M*, and PhD *$136.87M*.
- Claims were very low in early years and increased over time.Peak occurs around late 1990s to early 2000s *($77M–$97M range)*.Recent years show a sharp drop to around *$16M*.
- Claims are very evenly distributed across colors *($99M–$106M)*.Highest:**Turquoise** *$106M*, lowest: Yellow/Violet/Fuscia *$99M*.
- Customers with 0 claims account for the highest total ($1.36bn), then claim amount drops significantly as frequency increases:
    - 1 claim: *$296.14M*
    - 2–4 claims: all below *$80M*
 - Ford *$168M* and Chevrolet *$148M* have the highest claims.Lowest claims come from Volkswagen *$62M*.Other brands fall in a close range ($68M–$93M).
 - Income is fairly evenly distributed across all zones *($1.09bn–$1.11bn)*.Urban areas are slightly higher *$1.11bn*.
 - All zones have very similar average income *($147K–$148K)*.Highly rural is slightly highest, but difference is very small.    

 # Overall Insights
 - Opportunity to sell premium policies and add-on products.
 - Claims are a major cost driver, which can reduce profitability if not controlled.
 - Claims are influenced more by age, marital status, car type, and location,but not much by gender.
 - Most insurance risk comes from private car users, meaning policies should focus more on private vehicle risk management.
 - Fewer or no young drivers in a household is associated with higher claims, possibly due to older or more frequent drivers.
 - Claims decrease as education level increases, suggesting higher education may correlate with safer driving behavior or better risk management.
 - Older vehicle generations (especially around peak years) had higher claim activity, while recent years show improved safety or better insurance control.
 - Car color has almost no meaningful impact on claim differences.
 - Most claim value comes from customers who rarely claim, showing a large low-risk customer base.
 - Certain car brands are associated with higher claim costs, possibly due to usage volume, repair cost, or risk profile.
 - Insurance customers are evenly spread geographically, with no major income concentration in one zone.
 - Income level does not vary much by location, meaning pricing or policy strategy should not heavily depend on zone income differences.
 - The insurance system is stable, with claims well below total income.

# Recomendations:

- Give discounts or bonuses to customers with 0–1 claims to keep them loyal.
- Charge slightly higher premiums for customers with many claims to reduce risk.
- Brands like Ford and Chevrolet should have better risk checks or adjusted premiums.
- Since they make most claims, introduce safe driving programs for them.
- Encourage training to reduce accidents, especially for less educated drivers.

# Limitations:

- High claims may be due to more users, not necessarily higher risk.
- No information on driving habits, which affects claims.
- Very low recent claims may be incomplete or delayed data.
- Claims are not split into types (repair, medical), limiting deeper insights.
