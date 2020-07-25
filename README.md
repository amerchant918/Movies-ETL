# Movies-ETL

Extract, Transform, and Load datasets 

## Assumptions:
* When removing/cleaning data the assumption is that the data being dropped has very little relevance to the overall dataset analysis.
* When cleaning up the data using regular expressions the assumption is that majority of the forms have been captured and minimal rows might have variations
* The assumptions is that overall the data will follow a consistent format even in the future
* We assume based of our exploratory analysis (scatter plots) that Kaggle Data is more consistent and relevant than Wikipedia therefore Wikipedia data was dropped
* We assume columns with only 1 value provide little to no valuable information therefore we only preserve the columns with multiple values
