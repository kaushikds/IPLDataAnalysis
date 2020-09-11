# IPLDataAnalysis
This notebook is about practicing the data analysis steps of loading the data into a pandas dataframe and getting some basic information about the dataset using pandas functions:
* Loading data into a dataframe by using the pandas method - **.read_csv()**
* Printing the first 5 rows of the dataframe by using the pandas method - **.head()**
* Printing the Number of Rows and the Number of Columns present in the dataframe, or "shape of the data", by using the pandas method - **.shape()**
* Finding out the type of data present in each column in the dataframe by printing the dataframe's **dtypes** attribute

## Dataset Contains
* match_id - Unique Identifier for each match
* inning - 1st innings or 2nd innings
* batting_team - Name of the batting team
* bowling_team - Name of the bowling team
* over - Current over
* ball - Current ball of the over
* batsman - Name of the batsman on strike
* non_striker - Name of the batsman on non-striker's end
* bowler - Name of the bowler
* is_super_over - Is this a super-over (0 or 1 for NO or YES)
* wide_runs - Runs given as wide
* bye_runs - Runs given as bye
* legbye_runs - Runs given as leg-bye
* noball_runs - Runs given as no-ball
* penalty_runs - Runs given as penalty
* batsman_runs - Runs scored by the batsman
* extra_runs - Total extra runs (Wide, Bye, No-ball, Penalty)
* total_runs - Total runs from the ball (extra_runs, batsman_runs)
* player_dismissed - Name of the player dismissed (If out)
* dismissal_kind - How the player was dismissed (If out)
* fielder - Fielder involved in the dismissal (If any)
