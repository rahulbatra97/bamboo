# bamboo
A week 4 project from Sparta to clean and analyse a dataset using Pandas DataFrames and packages like seaborn and matplotlib to create visualisations.



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
1. dropping columns
2. removing duplicates
3. removing irrelevent rows
4. removing null and other values
5. standardise values? 
6. split columns
7. convert data types


notes: I have realised I should identify null values before removing duplicates as the duplicates could contain the missing values. 

actions: re-adjust the dataframe to include the duplicates, then run the code that identifies null values, see if any of the duplicates will contain the missing rankings and try to merge them. 





ACT 2
- visualisations with seaborn and matplotlib
- data insights, considerations & conclusions
- further questions and food for thought 

