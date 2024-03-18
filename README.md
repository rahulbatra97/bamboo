# bamboo
A week 4 project from Sparta to clean and analyse a dataset using Pandas DataFrames and packages like seaborn and matplotlib to create visualisations.

this repository includes a working file with informal notes and a FINAL file. For the final file please see the pandas_project_RB_final file. 


dataset: Google Play Store Apps
in this dataset we have Apps, their categories, ratings, reviews, installs, types, price,
content rating, and genres. 

motivations
Once the data is cleaned, some buisness questions could be:
- Identify the best ratings in regards to the number of reviews. 
- Most popular caegories by looking at categories to ratings 
- and reviews against type (free or paid)

blueprint

ACT I
- load in data
- turn the csv into a dataframe
- exemplify some techniques to first view what date we do have 
- clean/manipulate the data (keep in mind potential buisness style questions)

Data cleaning Methods: 
Combine_first (joins together dataframes selecting what information is kept. 
Dropping duplicates
dropping columns
removing null and other values 
convert data types, numeric and to DATETIME


notes: I have realised I should identify null values before removing duplicates as the duplicates could contain the missing values. 

actions: re-adjust the dataframe to include the duplicates, then run the code that identifies null values, see if any of the duplicates will contain the missing rankings and try to merge them. 


ACT 2
- visualisations with seaborn and matplotlib
- data insights, considerations & conclusions
- further questions and food for thought 

