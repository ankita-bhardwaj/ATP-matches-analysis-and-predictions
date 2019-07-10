# ATP-matches-analysis-and-predictions

# About the data used:
- Data collected from Jeff Sackmann’s repository on Github u Data from ATP Masters and Grand Slam tours for men’s singles matches. 
- Columns for player file columns are player_id, first_name, last_name, hand, birth_date, country_code.
- The columns for the ranking are ranking_date, ranking, player_id, ranking_points.
- ATP rankings are mostly complete from 1983 to the end of 2014. 1982 is missing, and rankings from 1973-1981 are only intermittent. 
- Initial data cleaning was required

# Data Cleaning:
- 1968 and 1969 had non- ASCII characters 
- Duplicate names such as Us Open and French Open for US Open and Rolland Garros 
- Conversion of date from string to date format: Year and Month had to be extracted from the tournament date string 
- Number of games in each match was not directly available, and inconsistent across years 
- Data for double faults, aces, break points saved were unavailable for years preceding 1985 
- Time of games was not available for US Open 1998 and Australian Open 1996

# Questions to be answered:
- Does number of aces served depend on the surface type? 
- Compare performance over years of the two GOATs 
- How has the average time of play changed over years at Grand Slams? 
- Have grand slam winners become older over time? 
- The mysterious pattern of Double Faults in tennis 
- How many times have the dark horses won? 
- What’s the future of tennis? 
- What affects a match win the most? Can we accurately predict match wins? 

# Prediction Accuracies:
- US Open : 71.19%
- Wimbledon: 69.01%
- French Open: 70.3%
- Australian Open- 69.2%

# Relevant Features for prediction:
Based on the p value of the independent variables, following features came out to be important:
- US Open- Rank, Age and Height of the players
- Wimbledon- Rank and Height of the players
- French Open- Rank and Age of the players
- Australian Open- Rank of the players

