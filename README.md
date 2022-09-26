# Election_analysis

 The purpose of This election audit is to determine the winner of the election and provide statistical information about the election process
 
 ## The process of determining the election results was as follows:

* Data was collected from excel spreadsheet eletion_results.csv and linked to our python file 
* Each vote in file contained the candidate’s name and county that the vote was received.
* Using the following code votes = candidate_votes.get(candidate_name) nested inside a for loop that went through each name listed in csv file this code will count the number of times that a candidate’s name appears on the spreadsheet and increase the value of "votes" by 1 
* For each line in the sheet total_votes increased by 1 regardless of the name on the ballot. vote_percentage = float(votes) / float(total_votes) * 100 was used to determine what percentage of the total vote was earned by each candidate. 
a second for loop was used after this for loop had concluded this would count the number of votes each candidate had and store the canidate with the greatest number of votes and the percentage of the votes they had earned. 
The results were then placed into a readable user-friendly format and saved to and external .txt file 
* This same process was repeated in order to determine the county with the highest voter participation.



With this information we can determine the winner of the election the margin by which the winning candidate took the Election as well as what county had the biggest turnout with this information future candidates can shape their campaigns to increase the chances of success by focusing on counties with high voter participation and looking at the successful candidates to determine how to shape their own messages in the future.
