Election Project
Data Source
Raw ANES election data obtained from electionstudies.org.
Process
This project analyzes third-party performance in U.S. presidential elections using historical election data.

start.ipynb

Loads and processes election data into a DataFrame.
Filters total votes for each party, including major and third parties.
3rd_party.ipynb

Focuses on third-party candidates by filtering out major party candidates (Democrats & Republicans).
Removes cases where major party candidates appear as third-party candidates due to ballot fusion (e.g., Farmer-Labor Democrats in Minnesota).
Analysis & Trends

Identifies third-party candidates and platforms with the highest total votes.
Determines the years when third-party candidates performed best.
Visualizes trends in third-party voting with a line graph.
Cleans data inconsistencies, such as null values and misclassified major party candidates.
Conclusions
Top Third Parties by Total Votes
Independent
Libertarian
Reform
Green
Most Successful Third-Party Candidates
Ross Perot (1992, 1996) – Reform Party
Gary Johnson (2016) – Libertarian Party
John Anderson (1980) – Independent
Ralph Nader (2000) – Green Party
Highest Third-Party Vote Shares
1980 – John Anderson (Independent)
1992 & 1996 – Ross Perot (Reform)
2016 – Gary Johnson (Libertarian)
This project provides insights into third-party electoral performance and historical trends in U.S. presidential elections.

