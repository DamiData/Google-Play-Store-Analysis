# App Optimization

### Introduction

The Google Play Store team has recently launched an exciting new feature designed to enhance the visibility of promising apps. This feature boosts app visibility in multiple ways, including higher priority in recommendation sections such as “Similar apps, Additionally, these promising apps receive a boost in search results visibility. This initiative aims to bring more attention to newer apps with high potential.

The  objective of this project is to identify which apps are suitable for promotion by Google. App ratings, provided by customers, serve as a reliable indicator of an app's quality. Therefore, the project aims to predict which apps will achieve high ratings, helping Google to effectively promote promising apps with the new visibility-boosting feature.

#### Data set 
The "Google Play Store" dataset provides comprehensive information on apps, including categories of apps, pricing, installs, and user reviews and ratings. With a focus on app optimization, it offers valuable insights into market trends, pricing dynamics, and user preferences within the app industry.

The dataset can be accessed [here](https://www.kaggle.com/datasets/madhav000/playstore-analysis).

##### Tool Used : Microsoft Excel

### Data Cleaning / Exploratory Data Analysis

The data processing involves cleaning the dataset to remove any inconsistencies, handling missing values, and ensuring the data is in a suitable format for analysis.

1. **Understanding the Origin of the Dataset and Each Column:**
   - Familiarize with the source of the dataset and the significance of each column.

2. **Duplicate a Copy of the Data:**
   - Create a backup of the original dataset to preserve the raw data.

3. **Remove Duplicates:**
   - Identify and remove duplicate records to ensure data integrity.

4. **Use Proper Function to Standardize App Names:**
   - Apply the Proper function to format app names consistently.

5. **Count and Address Missing Values:**
   - Utilize functions to count blank rows and address missing values appropriately.
   - Replace `NaN` with `0` where applicable and use "Varies with device" for current version discrepancies.

6. **Normalization of Data:**
   - Convert sizes from MB (megabytes) and KB (kilobytes) to a standardized unit using the IF function.
     - For sizes in MB, multiply by 1024 to convert to KB.
     - For sizes in KB, leave as is.
     
7. **Power Query and Pivot Tables:**
   - Use Power Query for advanced data cleaning.
   - Create pivot tables for comprehensive data analysis.
  
 ###  What-If Analysis (Goal Seek)
 To determine the number of installs needed to break even for the Study Check App, we performed a What-If Analysis using Excel's Goal Seek functions. This analysis helps us explore different scenarios for 
 optimizing app visibility and pricing strategies on the Google Play Store. 

 ### Problem Statement
 Google Play Store team is about to launch a new feature wherein, certain apps that are promising, are boosted in visibility. The boost will manifest in multiple ways including higher priority in recommendations sections (“Similar apps”, “You might also like”, “New and updated games”). These will also get a boost in search results visibility. This feature will help bring more attention to newer apps that have the potential.

### Analysis and Insights

##### Top 10 App Categories by Install
- List of top 10 app categories with the highest number of installs.

##### Content Rating Distribution Among Apps
- Analysis of content rating distribution among apps: How Age-Restrictive are Apps

##### Free vs Paid Apps
- Comparison between free and paid apps in terms of installs, ratings, and reviews.

##### Top 10 Most Rated and Reviewed Apps
- Identification of the top 10 apps with the highest number of ratings and reviews.

##### Top 5 Apps Reviewed and Rated
- List of the top 5 apps with the highest user reviews and ratings.

##### Most Expensive App Categories
- Analysis of the app categories with the highest average price.

### KPIs
- **Total Category Apps:** Total number of apps in each category.
- **Average App Size:** Average size of apps across all categories.
- **Total Installs:** Total number of installs across all apps.
- **Minimum and Maximum Size:** The smallest and largest app sizes.

## Recommendations

1. **Boost Visibility of Top Categories:**
   - Increase the promotion of the top 10 app categories by installs. This will leverage their popularity to drive more downloads and user engagement.

2. **Highlight Most Rated and Reviewed Apps:**
   - Promote apps that have high ratings and reviews as they are likely to attract more users. reviews can be used in marketing campaigns to build trust.



     

