# App Optimization

### Introduction

The Google Play Store team has recently launched an exciting new feature designed to enhance the visibility of promising apps. This feature boosts app visibility in multiple ways, including higher priority in recommendation sections such as “Similar apps, Additionally, these promising apps receive a boost in search results visibility. This initiative aims to bring more attention to newer apps with high potential.

The  objective of this project is to identify which apps are suitable for promotion by Google. App ratings, provided by customers, serve as a reliable indicator of an app's quality. Therefore, the project aims to predict which apps will achieve high ratings, helping Google to effectively promote promising apps with the new visibility-boosting feature.

#### Data set 
The "Google Play Store" dataset provides comprehensive information on apps, including categories of apps, pricing, installs, and user reviews and ratings. With a focus on app optimization, it offers valuable insights into market trends, pricing dynamics, and user preferences within the app industry.

The dataset can be accessed [here](https://www.kaggle.com/datasets/madhav000/playstore-analysis).

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

