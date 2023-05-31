# IPL-Analysis-PowerBI-Dashboard

A PowerBI Dashboard on IPL matches Analysis 


Steps:


1) Data transformation: (On Power Query)

. Preprocessed the year column and converted it to int type from string

. Changed misspelled team names from every column which contained team names

. Changed misspelled venue names from the venue column


2) Data Modelling:

. Connected the match id of table ipl matches and ipl ball to ball

. Created a new table called calendar consisting of all the dates of ipl matches. for time intelligent functions

. Connected the dates columns in calendar and ipl matches table


3) Data Visualization:

The project shows:

. Slicer i.e., a filter for every Season in IPL

. Season Winner 

. Orange cap holder 

. Purple cap holder

. Number of 6'

. Number of 4's

. Batting statistics (like runs, 6's, 4's, & strike rate) of every batsmen

. Bowling statistics (like wickets, economy, average, & bowling strike rate) of every bowler

. Matches won by Toss decision

. matches won by result type

. matches won at every venue by result type

. total wins by team
