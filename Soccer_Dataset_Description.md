# Soccer Dataset Description

Gracenote sports reporting for key sports is done by recording a set of discrete actions within a match, these are aggregated using business logic to give our customers data on the entire match, season and also to give us player and team statistics

This file is a sample data set from our reporting of Football / Soccer for actions occurring during the matches in various leagues. Not all events are included.

The files are in CSV format.

Teams.csv: This file contains a list of players representing various teams.

| Field     | Description                       |
|-----------|-----------------------------------|
| team_id   | A unique identifier for each team |
| name      | Team name                         |
| player_id	| A unique id for each player       |
| firstname	| First name for the player         |
| lastname	| Last name for the player          |
| birthdate | Birth date for the player         |

Game_Results.csv: This file contains matches played in leagues and their results.

| Field         | Description                                                       |
|---------------|-------------------------------------------------------------------|
| league_id	    | A unique identifier for league                                    |
| league_name	| League name                                                       |
| season_id 	| A unique identifier for each season                               |
| season    	| Season for the league                                             |
| game_id	    | A unique identifier for each game in the season                   |
| gamedate	    | Date that game took place                                         |
| team_id	    | A unique identifier for each team                                 |
| team_name	    | Team name                                                         |
| goals	        | Goals scored by that team in the match                            |
| penalty	    | Penalty score (if game went in the penalty shootout)              |
| result	    | Result of the match for that respective team. 0 - Loss, 1- Win    |