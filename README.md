# Exploratory-Data-Analysis

exploratory data analysis (EDA), which includes a variety of techniques used to better understand a dataset and discover hidden patterns & insights. 

common EDA techniques used by data scientists:

1. Exploring data: Viewing & summarizing data from multiple angles

Examples->
• Filtering
• Sorting
• Grouping

2. Visualizing data: Using charts to identify trends & patterns

Examples->
• Histograms
• Scatterplots
• Pair plots

# Exploring data

## Filtering

You can filter a DataFrame by passing a logical test into the loc [ ] accessor

• Apply multiple filters by using the “&” and “|” operators (AND/OR)

## Sorting

You can sort a DataFrame by using the .sort_values() method

• This sorts in ascending order by default

## Grouping

The “split-apply-combine” approach is used to group data in a DataFrame and apply calculations to each group

• You can group a DataFrame by using the .groupby() method
![image](https://github.com/user-attachments/assets/05621aa9-e0d6-4918-8685-1178fcbd0a39)

# Assignment: Exploring Data

From: Anna Analysis(Senior Data Scientist)

Subject: Happiest Countries of the 2010s?

Hi, 

The marketing team would like to share out the five happiest countries of the 2010s on social media. I’ve attached a notebook that another data scientist started with happiness data inside. I would recommend:

• Creating a list of each country’s highest happiness score,
and then sorting it from happiest to least happy country

• Creating a list of each country’s average happiness score,
and then sorting it from happiest to least happy country
Are there any differences between the two lists?

Thanks!

## Key Objectives

1. Filter out any data after 2010 and before 2020
2. Group the data by country and calculate the maximum happiness score for each one
3. Sort the grouped countries by happiness score and return the top five
4. Group the data by country and calculate the average happiness score for each one
5. Sort the grouped countries by happiness score and return the top five
6. Compare the two lists

# Visualizing data

## Data visualization in Pandas

You can use the .plot() method to create quick and simple visualizations directly from a Pandas DataFrame

## Pair Plots

Use sns.pairplot() to create a pair plot that shows all the scatterplots and histograms that can be made using the numeric variables in a DataFrame


![image](https://github.com/user-attachments/assets/ae62d677-0c87-4022-a6be-c2d977d886e8)

