# Election_Analysis
## Overview of Election Audit: 
The purpose of this project was to analyse the voter data for an election audit of a recent election in Colorado.This task is performed by Tom and his manager,seth. We analysed the voter datat using PYTHON script to give the following details initially:
1.  The total number of votes cast.
2.	A complete list of candidates who received votes.
3.	The number of votes each candidate received.
4.	The percentage of votes each candidate won.
5.	The winner of the election based on the popular vote.

The election commission has requested some additional data to complete the audit after the initial request:

1.The voter turnout for each county
2.The percentage of votes from each county out of the total count
3.The county with the highest turnout

##  Results:
Python and Visual Studio Code were used to analyse the election results CSV file that Tom has sent us. First we Ran a Python file in the VS Code.
 we were able to generate the following result after
 Perform Calculations,
 Creating  and adding to lists,keys and values to a dictionary,
 Using decision statements to check a condition,
 Using repetition statements to iterate through a list and dictionary,
 using loops and conditional statements,
 Writing print statements using f-string:
 
 
 The Initial analysis shows that:
    1. 369,711 votes were cast in the election.
    2. The candidates were
          Charles Casper Stockham, 
          Diana DeGette and 
          Raymon Anthony Doane.
    3. Charles received 85,213 votes,
       Diana received   272,892 votes, 
       Raymon received  11,606 votes.
    4. Charles won 23.0% of the votes,
       Diana won   73.8% of the votes and 
       Raymon won  3.1% of the votes.
    5. Diana DeGette won the election.
    6. Denver had the largest voter turnout.
  
  Election audit results were seen in the image as follows:  
 ![election result pypoll_challenge](https://user-images.githubusercontent.com/96032051/149817336-d7c4aab2-d049-4aeb-af3b-c123fdb68725.png)
 


 


 
 
#### How many votes were cast in this congressional election?
There were 369,711 total votes cast.

#### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
The three counties and their voter turnout which can be seen in the above results image  is as follows:
Jefferson: 38,855
Denver: 306,055
Arapahoe: 24,801
The percentage of votes in each county from the total votes is as follows:
Jefferson: 10.5%
Denver: 82.8%
Arapahoe: 6.7%

#### Which county had the largest number of votes?
 Denver had the largest voter turnout.


#### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
#### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Diana DeGette with 272,892 votes, which was 73.8% of the total votes.


## Election Audit Summary:
In summary, this script can be customized to serve as a guide for future election performance across other counties or even states, with some modifications.

  1.Modify the code to see county wise which candidate is the winner ; we can use this data to analyse the budget for future election campaigns. I would suggest to Use a vote percentage for each county voted for each candidate and using an if-else statement to print the results.This will print the candidate name, county name, and vote percent for each county.
  
  2.we can modify the code and write it to loop through the ballot IDs to ensure that there are no duplicates due to manual errors.
we can even modify the script to apply to states instead of counties in federal elections which can be a valuable resource for data analysing.
