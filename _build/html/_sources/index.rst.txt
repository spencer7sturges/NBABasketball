.. NBABasketball documentation master file, created by
   sphinx-quickstart on Wed Dec  5 13:30:05 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to NBABasketball's documentation!
=========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Background
#####

We wanted to look at the NBA, the reason being that the game has changed so much in the last several years. Players are shooting threes at an alarming rate. There are weekly awards that reflect players’ performances throughout 7 days. We specifically wanted to look at these award winners and see how much these players make. For those who lead the NBA in salary, are they winning this award? Is the money they are getting paid justified by their play? We used a “Player of the Week” data set in order to gather our initial data. We then screen scraped from ESPN to gather salaries from the last two seasons. 

Goal
######

We wanted to look at a these award winners from the last two full seasons and compare them to their salary. Which positions make the most and get paid the most? Is there a correlation between total amount of awards won and salary?

Methodology
#####

Our data will be posted in GitHub visible to the public. Essentially, we gathered data from the set, scraped from ESPN and then put both into dataframes and combined them. Then we visualized like this. 

Visualizations
#####



First graph shows the total amount of awards won for each player over the last two seasons.  Awards means the player winning the player of the week, and this is represented as awards for us.
******


.. figure:: Players_Hor_Bar_Graph.png

This shows that DeMar DeRozan and James Harden have the most awards in the last two seasons with 9. The reason the x-axis is showing only to 4.5 is that the column is real_value and for each award won, it increments by .5. LeBron James has 8 awards won. Then the next two are Stephen Curry and Russell Westbrook. What makes this horizontal bar chart really interesting is we have around 10 players who have won the award more than other players, and then we have a lot of the other players winning the award the same amount of times.

Our next graph shows the top 5 highest paid players
******

.. figure:: Top5PlayersSalary.png

Coincidentally, the top 5 most award winners are also the top 5 highest paid players. This means that these players who are getting paid the most are worth the money.  Also, this shows how important having a top player like these players are to their team.  Each of these teams that these players are on very successful teams.  For example, LeBron James and DeMar DeRozan are on the two top teams in the Eastern Conference, while moving to the Western Conference Steph Curry and James Harden are on the top two teams in the West.  Now this leads us to our next question, does salary correlate to amount of times the award is won? 

Does salary correlate to the amount of times the award is won?  Award would be the player of the week award.
*****

.. figure:: PlayersAwardsWon.png

We would say there is a trend that players who make more, do end up winning the award based on performance required with such a high contract. The NBA is a business and they will just buy you out if you don’t perform.

Let’s look at the value of each position:
*****

.. figure:: SalaryByPosition.png

You can see, Point Guards and Small Forwards are the most valuable. I tried to run a graph with the positions who won the award the most, but the null values have messed up the graph. But, we know that Small Forwards and Point Guards have the most awards won. We believe  this shows that those two positions are most valuable. But, that could be because the top players in those two positions.  Another thing to think about is the game of basketball is changing, with players shooting much more threes the bigs have to change their game.  So this could also be why the guards favor better in the game of basketball in today's game.

Since these are the cases with position and salary, do players of certain heights get paid?
*****

.. figure:: HeightsRealValue.png

There isn’t a lot of  correlation here. We believe that is due to the fact that positions in the NBA are becoming positionless. Heights of PGs are becoming up to 7 feet! It will be hard to look at salaries and height together.

Now we are going to look at if a players height correlates with the awards they have won.
*****

.. figure:: HeightsAwardsWon.png

Then we look at Height to awards won. There is a slight negative correlation here showing that the shorter you are (to a point), the more likely you are to win the award. 

One interesting we looked at was a bar graph of how many years in the league for each position.
******

.. figure:: ExperiencePlayerAwardsWon.png

The more experienced players are the ones more likely to win the award, and you see the most experienced players are PG and SF. This leads us to believe that paying these super young players may not be entirely worth the money.

Here is a distribution of the award winners:
******

.. figure:: BarExperiencePlayersAwardsWon.png

.. figure:: DistributionExperiencePlayersAwardsWon.png

Frequently, award winners are within the 5 to 6 year range, but we we’ve seen that the more experienced players win it most.  This also explains how underrated or undervalued experience players go sometimes.  The graphs above show how important 5 yeards can be to a player.  With this time this allows an NBA player to grow and improve his game.

.. figure:: ScatterExperiencePlayersAwardsWon.png

Here is an example of years in league and awards won. Clearly, you can see the cluster in the 5 to 6 years range, but from 8 to 14 have the highest award winners. The saying goes, “The best contracts are max contracts.” Since teams are capped on spending, it’s nice to retain invaluable players for a value that’s under their potential. For example, LeBron James who has been in the league for 14 years on the graph above, has multiple mvps and three championships. Clearly, underpaid at 35 million.

To go along with the graph above, we looked at a distribution of awards won:
*****

.. figure:: AwardsWon.png

Most of these players in the last two seasons have won an average of about two. It’s interesting to look at how the amount varies throughout two seasons. One might think that a different player would win it each week or even the same players through the season, but we can see there is some variation. 

We also looked at how teams rank in award wins:
****

.. figure:: TeamsSuccess.png

The top four teams were Rockets, Cavaliers, Warriors, and Raptors. Those have been the top four teams in the last two years. The Warriors and Cavaliers have been to the finals the last two years and they have the two highest paid players on their respective squads. I would say there is justification for paying those who win this award frequently.

Findings
#####

We found that players that win this award the most deserve to be paid. There are more predictors for teams to look at than just Player of The Week, but it’s a good start. There was a correlation between high salary and Player of The Week. I don’t think it’s causation but players are expected to perform when earning high amounts of money. We also found that teams that have these winners on their team exude success. Rockets, Raptors, Cavs, and Warriors have frequent winners and their teams are consistently at the top of the NBA. 

As an NBA GM, they definitely look at positions of players when drafting and signing. Conceptually, having five solid guys would be ideal, but in today’s NBA, if you don’t have a top PG or SF, you can’t succeed. Centers haven’t won the award as often as guards, but if we had to look more, we should look at different eras and categorize the seasons. Centers in the ‘80s and ‘90s were more valuable than guards, but the game has changed. 

Next time anyone watches an NBA game look for the team’s best player, if it’s a guard and small forward, the team’s record will reflect that. 



=================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
