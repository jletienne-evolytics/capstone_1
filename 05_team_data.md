# Team Matchup Data

Ok the bulk of the capstone project. Let's check the matches to see who won or lost their fantasy football matchup.


Let's just do week 1. We'll do one team and go from there can do one team.

***** Follow along at `notebooks/05_team_data.ipynb` !!!! *****


-------

It looks like matchups can be found here. <br>
https://docs.sleeper.com/#getting-matchups-in-a-league

We'll pass the league id and week 1 as parameters for `<league_id>` and `<week>`

We need to explore our data. Something let's us know we have a list of 12 teams


```
len(matchups), type(matchups)
```




We need the week, team_id, points scored, and opponent id


May need to install *pandas*

![](screenshots/Capstone%2017.png)


At this point go into the notebook called 05_team_data. notebooks/05_team_data.ipynb


![](screenshots/Capstone%2018.png)

You may need to create a folder called raw_data

![](screenshots/Capstone%2019.png)
