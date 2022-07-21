# Election_Analysis

## Overview of Project

### The Election Analysis Challenege is intended to take information from another data source, such as a .csv file (as in the challenge), and use Python to analyze the data using a series of loops and conditionals to determine the results and other information about the candidates and voters.

## Election Audit Results

1. The total votes from the election reached 369,711.
2. The county votes for each county were tallied along with calculating the percentage of votes.
3. The largest county or the county with the most amount of votes was Denver, with nearly 83% of the votes
4. The Candidate votes were outputed similar to the county votes. Each candidate was printed with their corresponding percentage and number of votes
5. Lastly, the winner of the election was outputed. Particularly, their name, number of votes and percentage

[Election Results](https://github.com/mbugyis/Election_Analysis/blob/main/analysis/election_analysis.txt)

## Election Audit Summary

  This python script can be used for nearly every election. The names of variables and way the code is written isn't particular to any country, state or region. This program is also useful because it allows one to automate the counting process. Specifically, when election results are in a separate file, it can be converted to a .csv file. Python is able to read .csv files and can conduct calculations via its script. 
  
  This script in particular takes in data from a [.csv file](https://github.com/mbugyis/Election_Analysis/blob/main/Resources/election_results.csv): candidate name, votes, and county. The script then keeps this information in either a dictionary or list which is used as a reference when making calculations for the election. The script runs calculations on votes, votes per candidate, calculates percent of votes, and the winner of the election. All of this information is outputed not only in the computer terminal, but a .txt file where the user of the election results can then convert to a more suitable file, such as word to display the results.
  
  Example of calculation:
  
          if (votes > winning_count) and (vote_percentage > winning_percentage):
            winning_count = votes
            winning_candidate = candidate_name
            winning_percentage = vote_percentage
