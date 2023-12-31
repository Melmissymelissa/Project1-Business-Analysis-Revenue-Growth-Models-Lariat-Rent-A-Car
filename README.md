# Business Analysis - Revenue Models
<a href="https://docs.google.com/presentation/d/1U7n5Ml21MTL6UKu5uvXBTpUwTUm49Tzh/edit?usp=drive_link&ouid=111495903765110507080&rtpof=true&sd=true">Link to presenation</a>
<a href="https://docs.google.com/spreadsheets/d/1uZELnS09dAQbjGamksFTnChbCyOrPEM9/edit?usp=sharing&ouid=111495903765110507080&rtpof=true&sd=true">Link to the Revenue Growth Model in Excel</a>

<!-- TABLE OF CONTENTS -->
   ## Table of Contents
   - [Introduction](#introduction)
   - [Data](#data)
   - [Data Preperation](#datapreperation)
   - [EDA](#EDA)
   - [Analysis](#analysis)
   - [Results](#results)

## Introduction
This project focused on conducting a robust business analysis for a (fictional company) Lariat Rent-A-Car, a leading car rental company. By analyzing historical sales data using Excel tools like VLookUp, pivot tables, and t-tests, we provided valuable insights.

I conducted exploratory data analysis to identify strategic scenarios for revenue growth. Key Performance Indicators (KPIs) determined the effectiveness of these scenarios. My resulting revenue growth models showcased a 20% increase in profits, while controlling operational costs.

Armed with comprehensive analysis and advanced Excel techniques, this project enables Lariat Rent-A-Car to make data-driven decisions, implement effective strategies, and achieve revenue growth and improved profitability.

## Data

The dataset used for this data analysis project consists of four Excel workbooks provided by Lariat, the national rental car company. Each workbook contains specific information related to the rental car fleet, costs, revenue, and branch locations. Here's a brief description of each workbook:

1. Car Revenue: contains data on the revenue generated by the rental car fleet. It includes details on the car ID, how long the car was rented, price per day, and other factors that contribute to the revenue stream. Link to this workbook <a href="https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/blob/main/project_root/raw_data/car_revenue.xlsx">Here</a>
2. Car ID Mapping: contains data on a mapping of car IDs to their corresponding make, model, and year. It serves as a reference for identifying specific vehicles in the fleet. Link to this workbook <a href="https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/blob/main/project_root/raw_data/car_id_mapping.xlsx">Here</a>
3. Car Costs: contains data on the costs associated with the rental car fleet. It includes information such as monthly car costs, insurance costs, and other financial aspects related to the vehicles. Link to this workbook <a href="https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/blob/main/project_root/raw_data/car_costs.xlsx">Here</a>
4. Branch Location: contains data on each branch location within the company. It includs information such as branchID, city and state of each branch.

## Data Prepratation 

1. Data Wrangle: Use VLOOKUP to consolidate raw data into a single workbook with five separate worksheets.
   
2. Created new data fields on the new consolidated data worksheet:
- Popularity Index: Calculates a count of rented dates per car in order to identify the most popular cars, using COUNTIF. (Average Popularity Index is 20)
- Popularity Score: Assigns a score based on the popularity index number. If the popularity index number is greater than or equal to 20, it is considered "Above" and assigned a score of "Above." For any other value, it is considered "Below" and assigned a score of "Below." This score helps determine the level of popularity for a particular car based on the given index number.
- Total Rev: Calculates the revenue of each car
- Yearly Costs: Calculates the yearly costs of each car
- Total Car Profit: Calculates the profit made by each car (Average profit per car is $5,627)
- Car Profit Score: Assigns a score based on the total car profit. If the total car profit is greater than or equal to $5,627 it is considered "Above" and assigned a score of "Above." For any other value, it is considered "Below" and assigned a score of "Below." This score helps determine the level of cars making a profit or not

![Screen Shot 2023-12-31 at 12 53 39 PM](https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/assets/142250108/d68038c0-5e48-4173-b3fa-460aef0a380b)

## Exploratory Data Analysis
I used Pivot Tables in Excel to answer these questions: 

1. How many cars are not making a profit?

![Screen Shot 2023-12-31 at 1 05 30 PM](https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/assets/142250108/6ddb38b2-e6f6-4ea4-a2ab-60c57ce50027)

2. What are the Top 10 Most Profitable Cars?

![Screen Shot 2023-12-31 at 1 35 45 PM](https://github.com/Melmissymelissa/Project1-Business-Analysis-Revenue-Growth-Models-Lariat-Rent-A-Car/assets/142250108/b2d182a4-41fd-4d78-80c3-af61149102e3)
