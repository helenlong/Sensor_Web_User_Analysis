# Sensor_Web_User_Analysis
This project consists of the following three steps:

Step 1: Import and clean data
In this part, following jobs were done:
   1. Web log data were first transformed to csv file; 
   2. Each column was closely examined and some of the columns were further devided to more    columns for future feature engineering;
   3. Column names were adjusted to be unified and clear;
   4. Missing values were dealt with by removing certain rows and columns. 

Step 2: Funnel Analysis
In this part, following jobs were done:
User activities were analyzed based on 'event' categories;
User activity levels at different events were demonstrated;
Funnel analysis was conducted and events that bottleneck the conversion rate was detected;
Suggestions were made based on the bottleneck events;
Conversion rate was calculated(4.1%).

Step 3: Model Building
In this step, two major things were done

First, relevant features were selected and engineered
A. number of visits per week
B. Average page stay time for each user
C. pageview times
D. btnClick times
E. index_leave times
F. about_leave times
G. courses_leave times
H. courses_play_leave times
I. latest_utm_medium (It indicates how user find Sensor website)

Second, Logistic Regression model was built
1. Achieved model accuracy of 99.7%
2. Most predictive factors were also identified:
    total number of visits per week; 
    users from cpc medium;
    users from mfeed medium;
    users from mcpc medium.
    index leave times;
    pageview times;
    button click times;
    courses play leave times;
    courses leave times;
    users from default medium.
