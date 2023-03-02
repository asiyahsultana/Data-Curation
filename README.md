# Data-Curation

The goal of this project was to collect data about highly rated TV programs during a specific season. TV program seasons typically run from September to May, so I decided to curate data about the top TV programs during the season of September 2003 to May 2004. I collected data from the Wikipedia page of highest rated TV programs from the past 7 decades. I did not use any specific API, however, I used the library pandas. Wikipedia's data is licensed under Creative Commons Attribution Share-Alike license.

I collected raw data from this website: https://en.wikipedia.org/wiki/Top-rated_United_States_television_programs_by_season#2010s

There were many datasets from this page, as it included data from each season for the past few decades. However, each dataset included the same attributes: the title of the TV program (string), its rank (integer), its network (string) and its rating (float).

I cleaned the data by creating a dataframe of specifically the data I was focused on, from September 2003 to May 2004. I then created a bar graph to compare the ratings of the top rated TV shows from that season.
