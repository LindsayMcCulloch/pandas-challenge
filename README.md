# pandas-challenge
This is the repository for Monash University Data Analytics Bootcamp Module 4 Challenge

Background

--------------------------------------------------------------------------------------------------------------------------------

You are the new Chief Data Scientist for your local government area. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyse the area-wide standardised test results. You'll be given access to every student's maths and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

Instructions

--------------------------------------------------------------------------------------------------------------------------------

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

# Local Government Area (LGA) Summary
Perform the necessary calculations and then create a high-level snapshot of the local government area's key metrics in a DataFrame.

Include the following:

Total number of unique schools

Total students

Total budget

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

Note: A passing grade is 50 or higher.

# School Summary
Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.

Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

# Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

# Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

# Maths Scores by Year
Perform the necessary calculations to create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.

# Reading Scores by Year
Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the codes provided to create four bins with reasonable cutoff values to group school spending. 

Use pd.cut to categorise spending based on the bins.

Use the codes provided to then calculate mean scores per spending range.

Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

# Scores by School Size

Use the code provided to bin the per_school_summary.

Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

Resources used:
--------------------------------------------------------------------------------------------------------------------------------

BCS Xpert Learning assistant 

Office Hours

Slack

https://stackoverflow.com/questions/72290465/how-to-get-average-of-a-list-in-pandas-dataframe

https://inspector.dev/how-to-round-numbers-in-python-fast-tips/#:~:text=The%20simplest%20way%20to%20round,rounded%20to%20the%20nearest%20integer.

https://stackoverflow.com/questions/61778610/output-both-bins-and-labels-column-in-pandas-binning

https://stackoverflow.com/questions/31593201/how-are-iloc-and-loc-different

https://stackoverflow.com/questions/61802149/sorting-values-in-a-pandas-series-in-ascending-order-not-working-when-re-assigne

https://numpy.org/doc/stable/user/absolute_beginners.html

https://stackoverflow.com/questions/22622571/difference-between-import-numpy-and-import-numpy-as-np

https://www.reddit.com/r/learnpython/comments/eeqmlh/why_bother_with_import_numpy_as_np/
