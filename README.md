# Election Project 
# Data Source 
-- Raws ANES election data obtained from electionstudies.org
# Process
 --Filters through election data to determine the most successful 3rd parties and the most successful 3rd party presidential candidates. 
 --The start.jpynb analyzes all major parties in Presidential elections during that time period by adding the data to a dataframe and filtering the total number of votes for each party. 
 --The 3rd_party.jpynb drills down the data by filtering out major parties and columns where democrat or republican candidates were showing up as candidates of 3rd Parties (ie farmer democrats in Minnesota). 
 --3rd_party assesses what 3rd party platforms and what 3rd party candidates receieved the most total number of votes during that time period.  
 --The program analyzes in what years 3rd party candidates were the most successful. It then prints out there names and party allignment. Trends in 3rd party votes over time are  represented in a line graph. 
 --It then drills down through the data and removes several inconsistencies related to null values and major candidates misrepresented as 3rd party in the data. 
# Conclusions 
--The parties with the most votes during this time period wwere 1. Indepdent. 2. Libertarian. 3. Reform. 4. Green 
--The 3rd party candidates with the most votes were Perot, Johnson, Anderson, Nader
--The largest percent of the total vote went to 3rd party candidates in the years 1980 for Anderson, 1992 & 1996 for Ross Perot, and 2016 for Gary Johnson. 
