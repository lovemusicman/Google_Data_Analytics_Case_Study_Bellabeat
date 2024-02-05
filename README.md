# Case-Study : Bellabeat
![image](https://github.com/lovemusicman/Google-Data-Analytics-Case-Study-Bellabeat/assets/39491191/991746c8-e80d-4c6f-b136-94fa9ca671a4)
![Bellabeat](https://bellabeat.com/)  

## Background
Bellabeat, a high-tech company that manufactures health-focused smart products. 
Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits.
Bellabeat’s cofounder Sršen believes that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth.

## Step 1: Ask
1.1 Business Task:  
  Analyze smart device usage data from non-Bellabeat products to uncover trends in consumer behavior and preferences.  
  Leverage these insights to recommend strategic directions for one Bellabeat product, aiming to enhance its market positioning and user engagement.  
  This analysis should guide the marketing strategy by identifying opportunities for growth and better alignment with consumer needs. 

1.2 Business Objectives:  
  1. What are some trends in smart device usage?
  2. How could these trends apply to Bellabeat customers?
  3. How could these trends help influence Bellabeat marketing strategy?

1.3 Key Stackholders:
  1. **Urška Sršen**: Bellabeat’s cofounder and Chief Creative Officer
  2. **Sando Mur**: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
  3. **Bellabeat marketing analytics team**: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy.

## Step 2: Prepare
2.1 Information on Data Source:  
* Data Source: [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit), a dataset generated by respondents through a distributed survey on Amazon Mechanical Turk from December 3, 2016, to December 5, 2016, and made available through Mobius on Kaggle.
* Dataset Description: This dataset contains personal fitness tracker data from thirty Fitbit users, distributed across 18 CSV files.
* Data details: this data set includes minute-level output for physical activity, heart rate, sleep monitoring, daily activity, steps, and heart rate that can be used to explore users’ habits.  
  
2.2 Data selection and Dataset preview:  
  Bellabeat's products wellness tracker" and watch have similar funtions with FitBit Fitness Tracker, they all track user's activity, step, calory and sleep.
* For analyzing daily data to track users' habits, I'm going to focus on **daily** and **WeightLogInfo** datasets.  
  * I found out dataset 'DailyActivity' already includes data on steps, activity and calories by using Excel, so the datasets
    I am going to use are 'DailyActivity', 'sleepDaily', 'weightLogInfo'.
## Step 3: Process
3.1 Cleaning the data:
* Import datasets:
  
The 'WeightLogInfo' file contains data from only 8 respondents, which is significantly less than the 33 found in other datasets. To avoid bias, this dataset has been skipped.

