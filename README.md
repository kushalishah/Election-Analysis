# Election-Analysis
Pypoll

# **Election Analysis Challenge**

## Overview of Election Audit
The purpose of this election audit analysis was to use Python to write algorithms that assisted with the confirmation and analysis of the election results cast in in Arapahoe, Denver and Jefferson. I did this by tracking candidate options, votes and using mathematical calulations to determine the winning count, and the overall winner.

## Election-Audit Results: 

* ### How many votes were cast in this congressional election?
  * The total number of votes cast was 369,711.

* ### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  * `county_vote = county_votes[county]
        county_percent = int(county_vote)/int(total_votes) * 100
        county_results = (
            f"{county}: {county_percent:.1f}% ({county_vote:,})\n"`
        
    Above is an copy of the code that was used to calculate the the percentage of total votes for each county. Denver had the largest votes at 82.8% while           Araphaoe had the least votes at 6.7%. For a further breakdown, here is the text file ![Image_of_election_analysis_txt]            (https://github.com/kushalishah/Election-Analysis/blob/main/analysis/election_analysis.txt)

* ### Which county had the largest number of votes?
  * Denver had the largest number of votes 306,055 and dominated 82.8% of the vote.

* ### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * <Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)>
 

* ### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * <Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%>
    
  * We can conclude that Diana DeGette had the most number of votes at 272,892 with a 73.8% dominance. 


## Election-Audit Summary: 
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

 - The script could be modified using joining another file of data with other counties and they could they could be modified by adding a gender column.
