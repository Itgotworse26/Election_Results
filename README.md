# Election_Results
Challenge assignment for Module 3

Congratulations! You’ve helped Seth and Tom submit the election audit results to the election commission. But wait! The election commission has requested some additional data to complete the audit:

* The voter turnout for each county.
* The percentage of votes from each county out of the total count.
* The county with the highest turnout.

Working from this module’s election_results.csv file, use for loops and conditional statements with membership and logical operators to find the requested results. Then, print the results to the command line and save them to your election_results.txt file.

Finally, you’ll provide a written analysis of the election audit for the election commission, including the new results and a clearly written overview of your methods. As with all written analyses, this will help your audience understand what you did and what they might be able to do with the data you presented.


Overview of Election Audit: The purpose of this project is to assess the voter turnout and percentage for each county, and determine which county had the highest turnout. This will allow Seth and Tom to determine whether the election commission had taken the proper steps to encourage turnout. In order to accomplish this task, a python program to read and organize the data by candidate and county will be needed. 

**Election-Audit Results**: When the program was run, this was the result of the analysis:

        Election Results
        -------------------------
        Total Votes: 369,711
        -------------------------

        County Votes:
        Jefferson: 10.5% (38,855) 
        Denver: 82.8% (306,055) 
        Arapahoe: 6.7% (24,801) 
        -------------------------
        Largest County Turnout: Denver
        -------------------------
        Charles Casper Stockham: 23.0% (85,213)
        Diana DeGette: 73.8% (272,892)
        Raymon Anthony Doane: 3.1% (11,606)
        -------------------------
        Winner: Diana DeGette
        Winning Vote Count: 272,892
        Winning Percentage: 73.8%
        -------------------------

* There were a total of 369,711 votes cast in the election.
    
* Jefferson County had 8,855 votes casted, making up 10.5% of the turnout. Denver County had 306,055 votes casted, making up 82.8% of the turnout. Arapahoe County had 24,801 votes casted, making up 6.7% of the turnout.
    
* Denver County had 306,055 votes casted, making up 82.8% of the turnout.
    
* Charles Casper Stockham received 85,213 votes, taking 23% of the ballots. Diana DeGette received 272,892 votes, taking 73.8% of the ballots. Raymon Anthony Doane received 11,606 votes, taking 3.1% of the ballots.
    
* Diana DeGette won with 272,892 votes, taking 73.8% of the ballots.

**Election-Audit Summary**: The election commission should rexamine their current outreach efforts to all counties. There is a massive gap in voter turnout in Denver County and Jefferson and Arapahoe Counties. Seth and Tom should ask the election commission to review what are their current efforts to increase voter turnout and why what may have worked in Denver County had a negligible effect in Jefferson and Arapahoe Counties. Another datapoint that might be helpful in future uses of this program would be to examine when and where the ballots were casted, whether they be in-person or sent by mail. Being able to examine where, where, and how voters are casting or sending their ballots could help determine when and why voters were or were not casting their ballots.       