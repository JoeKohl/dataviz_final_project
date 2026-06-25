# Data Visualization 

> Joseph Kohl. 

## Mini-Project 2

folder structure

data - dataset used (NBAchampionsdata.csv)

report - 
- KohlReport - pdf of analysis and conclusions
  
- Kohl-Analysis - html of Rmarkdown file
  
- Kohl-Analysis - Rmarkdown file

required packages : tidyverse,plotly,usmap,ggrepel,broom

Run each chunk in the Rmarkdown file in order to reproduce the analysis

I chose the NBA Champions Dataset because I like basketball and was curious as to what insights I would find in the data.
The dataset had stats for each game in the finals every year from 1980 to 2018.

The dataset had 2 entries with the team name input wrong one had 'Heat' (with the single quotes) and another
had Warriorrs instead of Warriors, I manually fixed these before doing my analysis.

The visualizations showed some interesting results specifically, looking at the map shows how dominant
regions are with Texas and California winning 21 of the 38 championships despite there being
dozens of other teams. This surprised me even though I knew that teams like the Lakers won a
lot in this timeframe.

The linear regression also yielded interesting results, assists were the most impactful on point scoring 
which makes sense because an assist can only happen if someone scores. More interestingly however, 
offensive rebounds had a smaller impact than total rebounds. I would have thought the opposite as an 
offensive rebound is almost always another scoring opportunity, whereas a defensive one wouldn’t necessarily 
turn into a scoring chance. 

I altered all of the graphs to make them more color-blind friendly palletes, which resulted in cleaner easier to read graphs.
I chose to redesign my regression chart as I realized it would be near impossible to decode for people who didnt know statistics or regression numbers.
Now it is color coded to show what variables are and aren't signifigant and those that are, along with their imact on scoring. 

Old Chart: 

<img src="https://raw.githubusercontent.com/JoeKohl/dataviz_final_project/main/figures/oldChart_2.png" width="70%" height="70%">

New Chart: 

<img src="https://raw.githubusercontent.com/JoeKohl/dataviz_final_project/main/figures/redesign_2.png" width="70%" height="70%">
