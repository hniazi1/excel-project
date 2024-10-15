# Project Details
In this project, I had to clean, model, and analyze data to create insights to present to clients. There were multiple different datasets to work with containing different columns and values. The goal was to work around different focus questions in order to present data significant to the research question.
## Methodology
The first step was to identify which datasets will be required to answer the business question- what are the top fice categories with the largest popularity.
The data cleaning occurred in the ReactionTypes-2.csv file as it contained multiple errors and null values that needed to be cleaned and corrected. 
    The data was cleaned by:
        removing rows that had missing values.
        changing the data type of some values within a column.
        removing columns that are not relevant.

The second step involved data modeling in which the workbook.csv file was incorporated and merged using different tables in order to figure out the top 5 categories. The final table was created merging data from the ReactionTypes-2.csv tables. 
    Formulas that were used in Excel to merge and organize the data were:
        VLookUp - to join and merge different tables
        Sum if - to add up the total scores for each category to figure out the top 5 performing categories
    The result should include one spreadsheet (workbook.csv) that contains a cleaned dataset

The last part of the project included creating a presentation dataset (Task 3_Final Content Data set.csv) to populate the dataset with the top 5 content categories and thinking of various ways to present the data in a graphical format. A pie chart was best suited as there were 5 categories and their percentages were easier to analyze once the data was cleaned and analyzed. It appeared that animals were the most popular category.
### Conclusion
After cleaning and modifying the datasets, it was clear that the category of "animals" had the most reactions (1,897). In order to find the most popular category, the COUNTIF formula was used in order to count the frequency of this category as well as the sum of the reactions. A pivot table was created where the group "Category" and "Count of Occurrences" was made to portray the data. The MAX function was used to find the highest value from the grouped counts. 
