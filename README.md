# Election_Analysis

#Overview of the Election Audit
The Colorado Board of Elections tasked us with auditing Congressional Election Results in one of the precincts, made up of 3 counties.  The project focus was to breakdown the number of votes cast for each candidate and determine the winner of the election based on the popular vote.  We were also asked to determine how many votes were cast in each county and show where the highest turnout was.  
#Election-Audit Results
•	There was a total of 369,711 votes cast throughout the 3 counties in this election.
 
•	The breakdown of the casted votes by county is as follows:

 

•	It was found that Denver had the highest voter turnout.
 
•	There were 3 candidates in this election and the vote breakdown is as follows:

 

•	The winner of the Congressional Election by receiving 73.8% of the votes was candidate Diana DeGette.
 
#Election-Audit Summary
The script we used to determine the Election Results is very versatile and can be used for any Election with a few modifications.  Here are a few examples for your consideration:
•	Inside every County there are Towns that might have their own elected officials, whether it be a Town Council or Board of Education.  A modification can be added to track different elections within the same dataset.  By adding a column of the dataset that shows what position the vote was cast for, we can then access that using a new variable(position) to find that column, and if statement to separate the votes for each selection.
•	This script can also be used for multi-state elections.  We can still use the existing code to track county results but add in another for loop to track the votes by state.  We can write the high-level results to a text file and also send those results to an excel file where it can be filtered more easily.














