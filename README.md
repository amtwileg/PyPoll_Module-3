# README

## Overview of Election Audit
The purpose of this election audit analysis is to determine if the actual voting data matches what was reported.

## Election-Audit Results
* How many votes were cast in this congressional election?  **369,711**
* Breakdown of the number of votes and the percentage of total votes for each county in the precinct:

  * County: Jefferson has: 10.5% of total votes with 38,855 votes.
  * County: Denver has: 82.8% of total votes with 306,055 votes.
  * County: Arapahoe has: 6.7% of total votes with 24,801 votes.

* Which county had the largest number of votes? **Denver**
* Breakdown of the number of votes and the percentage of total votes each candidate received:

  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)

* Winner of the election: **Diana Degette**
* Election winner vote count: **272,892**
* Election winner vote percentage: **73.8%**

## Election-Audit Summary
The script, `PyPoll_Challenge.py`, has been instrumental in supporting the audit detailed in this README. Furthermore, I advocate that this script could be extended to work - with some modifications - for any election. Two examples of how this could be done:
1. Convert the script to take two inputs: the path to the election data, and the desired output path for the results. This is useful so that we could run this script on multiple election result files simultaneously.
2. The script could be modified to handle different types of flat files (more than just csvs). Perhaps we want to be able to handle fixed-length formatted files or even just different delimiters (such as pipes, |).
