# Exploring Obesity Patterns in Latin and North America
 by Dylan Sedeno and Rayner Morla

### Project Overview

- The datasets we acquired had data on unidentified individuals the data provided us with their sex, age, height, weight, obesity level, the number of days they are active each week, and data unnecessary to our topic.
  
- The different units of measurement, confusing names, and other issues required deep cleaning, formatting, and erasing
  
- Extra columns were made and data values were calculated/converted.

- This study aims to compare the BMI disparities between genders and physical activity engagement within the Latin American and North American regions

 ### Project Data
 
 - [Estimation of Obesity Levels Based On Eating Habits and Physical Condition](https://www.kaggle.com/datasets/niharika41298/gym-exercise-data?resource=download](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition))
 - [Obesity prediction](https://www.kaggle.com/datasets/rahul2699/workout-information]](https://www.kaggle.com/datasets/mrsimple07/obesity-prediction/data))

#### [Project Presentation](https://docs.google.com/presentation/d/1nau63EudZ5EkriKWWj5F0DoEIlhbmWWHaBcQ8ixIQ-8/edit?usp=sharing) 

#### [Trello](https://trello.com/invite/b/ZRrmOmVJ/ATTIafa1ac2621759ad7215a627eee79191bE37161D1/week-3-project-board-for-github)

### Major Obstacle 

- This project was fun to work on, and the insights we gained were interesting. There were a few obstacles we encountered that put our newly acquired skills to the test. Finding the data proved to be time-consuming taking up a good 3 hours on day one. 
- After addressing prior challenges, we encountered discrepancies in BMI values between the regions. Latin American data displayed unusually high BMI values, reaching the 90s, typical the max is 40 for Class 3 obesity. We almost looked for new data sources before realizing the issue: BMI calculations in Latin America omitted squaring the height, resulting in inflated numbers.
- The biggest obstacle we had to deal with was figuring out how to display the data we had. What way to display this data that is easy to understand, and that allows everyone to see the insights we discovered? 

### Question

- Is there a significant difference in BMI levels between genders across different age groups, and does this difference vary depending on whether individuals engage in physical activity or not?

### Data Wrangling and Cleaning

The data cleaning came with some challenges, we had to fix formatting between the datasets so the units of measure were the same, and the classification of obesity needed to be the same all over and easy to understand. There was no missing data to deal with and only a few duplicates  were caught.
The units of measure were scattered between the metric system and the imperial system.  We settled on the metric system for all units used.
The classification of obesity levels for the Latin America data was more specific than North America’s. The data had different levels to overweight (ex overweight level II) and obese (obese level III). This was changed to match the North's data.

### Exploratory Data Analysis

- With our EDA we were looking for patterns showing a correlation between BMI and any other variable we have.
- We got our datasets from Kaggle, 1000 rows of data for North America and 2111 for Latin America. After cleaning and removal of duplicate data Latin America had 2086 rows of data. 
- There was enough data from the Latin America dataset to calculate the BMI of each unknown individual.

### Business Opportunities for Improvement

For a company reaching its target audience is essential, if they are not reaching their audience they will surely perish. Part of this is knowing where to focus your efforts: what age demographic?  what gender?  what region? These questions need to be answered so companies can be more effective in reaching who they want to reach.  This is where our project comes in, we aim to help companies in the health and wellness section to better reach their audiences. For this time our efforts are focused on North American and Latin American audiences. 

