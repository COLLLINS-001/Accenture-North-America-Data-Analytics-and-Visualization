In this project I am working as a Data Analyst at Accenture.
I work within a larger team, where each member has a different role and level of responsibility.
My team has been assigned a new project for a client called **Social Buzz**.

**DATA UNDERSTANDING**
The client has sent through:

  7 data sets - each data set contains different columns and values
  A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.

There is a lot of information here and it’s easy to get lost in the data. So, to make sure I am using the right data to answer the business questions I followed these steps:

  Requirements gathering
  Data cleaning
  Data modelling
Definitions of different data types:

    String - Sequence of characters, digits, or symbols—always treated as text
    UUID - Universally Unique Identifiers
    Array - List with a number of elements in a specific order—typically of the same type
    Integer - Numeric data type for numbers without fractions
    Timestamp - Number of seconds that have elapsed since midnight (00:00:00 UTC), 1st January 1970 (Unix time)
I identified Reaction, Content, and Reaction Types as our relevant data sets.

To clarify why I made this selection:

  The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
  As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
  We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
  So, to figure out popularity, I’ll have to add up which content categories have the largest score.

DATA CLEANING
I cleaned the data by:
 
  removing rows that have values which are missing,
  changing the data type of some values within a column, and
  removing columns which are not relevant to this task.

DATA MODELLING
To figure out the top 5 categories, I did data modelling following these steps:

1. Created a final data set by merging your three tables together

    Using the Reaction table as my base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set. 
     

2. Figure out the Top 5 performing categories

    Add up the total scores for each category.

DATA VISUALIZATION AND STORYTELLLING


