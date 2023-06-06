# Lottery_Powerball_Winning_Numbers_2010
First we explain that we imported the dataset from "https://data.ny.gov/api/views/d6yy-54nr/rows.xml?accessType=DOWNLOAD"
So please modify the file path accordingly to run the code.
Next we just display 10 rows from the dataset.
We then begin the data cleaning process, we check for missing values, delete the rows with missing values (we can't fill the missing information).
The winning numbers contains 6 pairs of numbers, for the analysis we needed to divide each pair in a different column.
We then checked once again for any missing values then changed the data types accordingly.

Once the data has been cleaned, we begin replying to the questions we have set during our project plan presentation.
For the majority of them, we included a graph for the data visualisation part.
Lastly, we attempted to add a graph that is a function of the odds of winning the lottery for every number of attempt/lottery participation up to ten million.
Sadly my computer couldn't handle such an operation so instead, we just computed the probability of winning for each of these numbers: 1, 1 million and 10 million.
