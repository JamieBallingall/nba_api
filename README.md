# NBA API demo

A proof-of-concept / demo for the `nba_api`

# To create the environment from scratch
```
conda create -n nba python=3.12
conda activate nba
conda install pandas
pip install nba_api
```

Then run
```
python main.py
```

Expect to see a large printout of a dictionary object beginning:
```
PLAYER_ID SEASON_ID LEAGUE_ID     TEAM_ID TEAM_ABBREVIATION  PLAYER_AGE  GP  ...   REB  AST  STL  BLK  TOV   PF   PTS
0     203999   2015-16        00  1610612743               DEN        21.0  80  ...   560  189   79   50  104  208   796
1     203999   2016-17        00  1610612743               DEN        22.0  73  ...   718  359   61   55  171  214  1221
2     203999   2017-18        00  1610612743               DEN        23.0  75  ...   803  458   90   61  210  212  1385
```

We are using the API library:
https://github.com/swar/nba_api

There may be additional data available at through other libraries. See:
https://medium.com/@cristianvaldez85/nba-data-using-python-82ebc0e19398
