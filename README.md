# Written Analysis of the Election Audit

## Project overview
A Colorado board of election employee has asked us to complete the following tasks in order to finalize the election audit of a recent local congressional election

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who receuved votes.
3. Calculate the total number of votes each candidate received.
4. Calcualte the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate resultes were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Challenge Overview
Great challenge to get some good understanding on how to use python for data analysis. 
As shown in attached code, we also practiced saving output into .txt file, which is very useful.

with open(file_to_save, "w") as txt_file:

    # Print the final vote count (to terminal)
    election_results = (
        f"\nElection Results\n"
        f"-------------------------\n"
        f"Total Votes: {total_votes:,}\n"
        f"-------------------------\n\n"
        f"County Votes:\n")
    print(election_results, end="")

    txt_file.write(election_results)
The main challenge was folliwing the synthax of the script. I was able to make the code work by following the template and running it until it did.

## Challenge Summary

Dear comission, please, note this code can be used for any election, such as Presidential by state or Congress. All that would need to be done is some modification to the script. As you can also see, this code will provide the board with all neccessary numbers and infomration needed for your work. I hope you find that universal capability attractive and that it makes you interested in this code.
