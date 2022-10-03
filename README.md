# Election_Analysis
This analysis is to audit the US Congressional precinct elections in Colorado.

# ELECTION ANALYSIS

## INSTRUCTIONS

* Overview of Election Audit: The purpose of this analysis is to audit the results of the US Congressional Princinct in Colorado. The audit answers the following questions;
1. The number of votes cast in the election.
2. A breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3. The county with the largest number of votes.
4. A breakdown of the number of votes and the percentage of total votes each candidate received.
5. The vote count and percentage of the winning candidate.

# Resources

  * Data Source: election_results.csv
  * Software: python 3.7.6, VSCode 1.71.2

# Election-Audit Results: 

* How many votes were cast in this congressional election?

Per the analysis, there were a total of 369,711 votes cast in the election.


<img width="436" alt="Total number of election votes" src="https://user-images.githubusercontent.com/109445468/193664335-467d6ead-570b-4f53-af92-0155c817ca60.png">

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Breakdown:

    Jefferson had 10.5% of the votes which amounted to 38,855 votes.
    Denver had 82.8% of the votes which amounted to 306,055 votes.
    Arapahoe received 6.7% of the votes which amounted to 24,801 votes.

<img width="436" alt="Total vote and percentage" src="https://user-images.githubusercontent.com/109445468/193664413-024ac553-5b75-4847-aed6-b64d6e3ff865.png">

* Which county had the largest number of votes?
Denver was the county with the largest number of votes.

<img width="614" alt="county with the largest vote" src="https://user-images.githubusercontent.com/109445468/193664478-2397c689-169d-4abf-b26a-0d1adc011630.png">

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    Charles Caper Stockham had 23.0% of the votes which amounted to 85,213 votes.
    Diana DeGette had 73.8% of the total votes which amounted to 272,892 votes.
    Raymon Anthony Doane had 3.1% of the votes which amounted to 11,606 votes.
    
<img width="614" alt="number and percentage for each candidate" src="https://user-images.githubusercontent.com/109445468/193664609-8a403c11-d3e9-4862-b37e-927c5ad3ee95.png">

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette won the election with a percentage of 73.8% of votes which equates to 272,892 of the votes.

<img width="614" alt="vote count and percentag winner" src="https://user-images.githubusercontent.com/109445468/193664711-161d2e32-c895-4b1e-b21d-35c2587d1943.png">

# Election-Audit Summary: 

The purpose of this audit was to be able to replicate this analysis in similar elections.

Example 1: Adding a Prompt for the Input File

Currently, the script only accepts input from one file. the information from the election must be overwritten in this file in order to audit another election.  To save the input data for later use, the user can be prompted with a file name to read. The modification will look like this;

file_to_read = input("file name to read, file sextension:")
file_to_load = os.path.join("Resources, file_to_read)

The "election_results.csv" file will be replaced with a different file.


