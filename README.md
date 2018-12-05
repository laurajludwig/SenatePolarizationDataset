# Senate Polarization

## Data Source
Data was sourced from Voteview.com. Senate sessions of member voting from the 76th through 114th (excluded 115th) sessions of Congress.

**Citation:**  
Lewis, Jeffrey B., Keith Poole, Howard Rosenthal, Adam Boche, Aaron Rudkin, and Luke Sonnet (2018). *Voteview: 
Congressional Roll-Call Votes Database.* [https://voteview.com/](https://voteview.com/)


## Data Objective
The purpose of this dataset is to build a dataset that can be used to visualize the polarization of Congress over time. The measure built for polarization of Congress, specifically the Senate, is based on whether members voted the same way in a vote. The Python file in this repository walks through how this was done iteratively. It also merges in the human-readable fields for usability.

## Assumptions
* A "Yea", a "Paired Yea" and an "Announced Yea" were all counted as a vote for the measure.
* A "Nay", a "Paired Nay" and an "Announced Nay" were all counted as a vote against the measure. 
* Abstentions, absences and other non-vote voting statuses were excluded for the purpose of this analysis.
