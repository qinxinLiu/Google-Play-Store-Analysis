## **Business Problem Statement:**

**Main Objective:** Gain understanding of the app market by analyzing the Google Play Store Apps dataset.

### Subgoals: 
1. Recognize the features that lead to an app's success;
2.  Examine user sentiments toward the app
3. Make suggestions to app developers on how to improve the app performance and user experience of their apps.

### SQL Quries: 

- **Dataset Overview:** 

The total number of distinct apps and categories within the dataset.


- **Examine App Counts and Categories**

Obtain the number of apps in each category as well as the unique app categories.

-- There are `9636` apps and `33` categories in total.  Family, Game, Tools, Medical, and Business categories have the largest number of apps.


- **Top-Rated Free Apps**

Determine the top-rated free apps.

-- The there top-rated free apps are Hojiboy TojBoyev Life Hacks, American Girls Mobile Numbers, Awake Dating and Spine. Most of them come from `COMICS` and `DATING` categories.


- **Most Reviewed Apps**

Identify the apps that have received the most reviews.

-- The most reviewed app is GollerCepte Live Score from `SPORTS` category followed by Ad Block REMOVERS from TOOLS category.

-- Most of the other apps with many reviews are  are from `SPORTS` and `SHOPPING` categories


- **Average Rating by Category**

Determine the average rating for every category of apps.

-- The category has the highest average rating is `EVENTS`


- **Top Categories with the Most Installs**

Determine which app categories have received the most installs overall.

-- Top 5 categories with the most installs are `FAMILY`, `GAME`, `TOOLS`, `MEDICAL`, `PRODUCTIVITY`


- **Average Sentiment Polarity by App Category**

Examine each app category's average sentiment polarity based on user reviews.


- **Sentiment Reviews by App Category**

Present the sentiment distribution among the various app categories.

-- `GAME` category has the most positive sentinment reviews

### Create PowerBI Dahsboard: 

- Data Cleaning: Replace `NaN` with null values, change data type.
  
- Create Measures

    `Total Apps = COUNTROWS(DISTINCT('googleplaystore'[App]))`

   `Total Categories = COUNTROWS(DISTINCT('googleplaystore'[Category]))`

- Data Modelling
  
  <img width="602" alt="截屏2024-02-03 21 55 04" src="https://github.com/qinxinLiu/Google-Play-Store-SQL-PowerBI-End-to-End-Project/assets/67852322/0bab31d3-d319-430e-a2a0-89952e450d1f">

- Dashboard

  <img width="1045" alt="截屏2024-02-03 22 29 59" src="https://github.com/qinxinLiu/Google-Play-Store-SQL-PowerBI-End-to-End-Project/assets/67852322/e87f84cf-3e7a-4237-979f-b8ab23d2f849">



### Insights: 

Eight thousand apps in the Google Play Store provide the basis for these insights:

- The categories with the highest number of apps are Family and Games.

- The top two categories with the highest ratings are games and personalization.

- The two most popular categories with the most installs are games and communication.




