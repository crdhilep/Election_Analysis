# Election Audit with Python
Click here to view the Python file: [Election Analysis](https://github.com/crdhilep/Election_Analysis/blob/main/PyPoll_Challenge.py)

## Overview of Election Audit
Assisting a Colorado Board of Elections employee Tom in an election audit of the tabulated results for U.S. Congressional districts in Colorado.
Once Colorado Board of Elections counts the votes cast by three primary voting method, we will generate a vote count report including all following audit tasks:

1. Calculate the total number of votes cast.
2. Calculate the voter turnout for each county and determine the county with highest voter turnout.
3. Get a complete list of candidates who received votes.
4. Calculate the total number of votes each candidate received.
5. Calculate the percentage of votes each candidate won.
6. Determine the winner of the election based on popular vote. 

### Resources
[Election Results Data](/Resources/election_results.csv)
The data presented includes three columns: ballot ID, county, and candidate name.

## Election Audit Results
Below image shows the summarized election results based on our analysis.

![Election Results](/analysis/election_results.png)

1. The total amount of votes cased in the congressional election was 369,711

2. Denver county received the most votes within this election. Denver leads with 306,055(82.8% of total votes) followed by Jefferson with 38,855(10.5% of total votes) and Arapahoe with 24,801(6.7% of total votes) votes.

| County Name | Total Number of Votes by County | Pencentage of Votes by County |
| --- | --- | --- |
| Arapahoe | 24,801 | 6.7% |
| Denver | 306,055 | 82.8% |
| Jefferson | 38,855 | 10.5% |

3. Canditates Lists, Totals Votes they received and their percentage

| Candiate Name | Total Number of Votes | Pencentage of Votes | Candiate Position |
| --- | --- | --- | --- |
| Charles Casper Stockham | 85,213 | 23.0% | 2nd |
| Diana DeGette | 272,892 | 73.8% | 1st (Winner) |
| Raymon Anthony Doane | 11,606 | 3.1% | 3rd |

4. Winning Canditate

    Diana DeGette received the most votes, which was 272,892 out of 369,711.

## Election Audit Summary

This script helps to automeate the process of tabulating the Election Results. 
With minimul modification(changing data set), this script can be use nation wide.
This script can also be modified to determine patterns among the characteristics. We could get popular votes by county against each candidate. This would allow us to see which candidate was the most popular within a county or geographical area.
