# Election_Analysis

## Overview of Election Audit
The purpose of this project is to use Python to write algorithms that assist in the confirmation and analysis of election results.
In this analysis, we calculated the number of total votes, the number of votes, and percentage by county and by candidate, and presented the largest county turnover and the winner.
The result was written to a text file, which will be sent to the election commission.


## Election-Audit Results
Please, find below the results of the Election-Audit Results, containing screen shots of the results from Visul Studio code:

- The total votes in this congressional election was 369,711.

![image](https://user-images.githubusercontent.com/108500573/179425837-256b36d5-bd92-4ae7-a90c-71c0a9b166d9.png)

- Breakdown of the number of votes and the percentage of total votes for each county in the precinct:

![image](https://user-images.githubusercontent.com/108500573/179426289-05229109-992f-4cbe-aa7a-b6e86e84ff2c.png)


- Denver was the county that had the largest number of votes

![image](https://user-images.githubusercontent.com/108500573/179426509-9f2ef40d-200f-4939-ad03-b5d7360a7953.png)

- Breakdown of the number of votes and the percentage of the total votes each candidate received:

![image](https://user-images.githubusercontent.com/108500573/179426532-c3f2c227-f0ec-4e4a-95dc-1c70c4b548a4.png)

- Candidate that won the election, the vote count, and the percentage of the total votes:


![image](https://user-images.githubusercontent.com/108500573/179426545-3a31a53a-1490-4c6c-871a-23230a472eab.png)


## Election-Audit Summary
The purpose of this script is to take an external file containing all votes (transactional data) and output the election results for audit.
With some modifications, it would be possible to use the script for any election.
We can define a new field called "electionId", which would be the Id of that particular election, and use it to calculate several election results with the same script. e.g. electionId: "presidential2022" for presidential election; "congress2022" for congressional election; etc.
We could also include a date field to get participation metrics, like most popular voting day, distribution analysis by day, etc.
