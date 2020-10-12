# Election_Analysis
## Overview of Election Audit
In order to complete the election audit of a local congress election, the Colorado Board of Election needs the following information to be delivered:
1.	Total number of votes cast.
2.	A breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3.	The county with the largest number of voters.
4.	A complete list of candidates who received votes, the total number of votes each candidate received, and the percentage of those votes per candidate.
5.	The winner of the election based on popular vote.

## Resources
-	Data source: election_results.csv
-	Software: Python 3.7.6, Visual Studio Code 1.50.0

## Summary
The analysis of the election shows that:
1. **The total amount of votes in the election were:** 369,711.

2. **The counties in this analysis and their total votes and their percentages are as follow:**
  * **Jefferson**:  10.5% (38,855)
  * **Denver**:  82.8% (306,055)
  * **Arapahoe**:  6.7% (24,801)

3. **The county with the largest number of voters was:** Denver.

4. **The candidates, their percentage and their votes result were:**
*	**Charles Casper Stockham** received 23.0% of the vote and 85,213 number of votes. 
*	**Diana DeGette** received 73.8% of the vote and 272,892 number of votes.
*	**Raymon Anthony Doane** received 3.1% of the vote and 11,606 number of votes.

5. **The winner of the election was:**
Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

When the Python script is run a txt file will be populated with the information above and will look as follows:
![Election_results](https://github.com/KatiuscaQ/Election_Analysis/blob/main/Resources/Election_results.PNG)
 
## Election Audit Summary
After studying the _*election_results.csv*_ file provided by the Colorado Board of Election, and creating a Python script to delivered the information requested by the election commission, I can demonstrate that the script could be used in other elections -with minor changes- examples as follow:
1.	Information from other counties (or states) could be analyzed with this script by editing the script on line 6 to point to another file.

![file_to_load](https://github.com/KatiuscaQ/Election_Analysis/blob/main/Resources/file_to_load.PNG)
 
2.	By changing the variables, the results would be directed toward another election analysis. Examples if the new file has information about demographics the analysis could show information based on voters age, parties, or ethnicity.
