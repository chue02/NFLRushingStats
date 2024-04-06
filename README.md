# RUNNING OFFENSE ANALYSIS
How important is the run game to NFL offenses and general team success?
- In essence: **should RBs be paid?**

# MOTIVATION
Before the 2023 season, there was a prominent controversy regarding running back's contracts. They were noticeable lesser than other skill position groups, particularly wide receivers. 

Running backs argued they added significant contributions to their team's offenses. However,  conventional wisdom stated they did *not* contribute as much as they claimed to due to a variety of factors, such as the running game's diminished significance in team and offensive success.

Amongst Giants fans such as myself, the debate was particularly polarizing since we achieved unexpected success despite our rather middling passing offense. I wanted to use data to answer the following questions:
  * Does the data support the hypothesis that it is worth giving a large contract to a running back? 
  * Is it worth investing non-insignificant portion of the team's capital on a star running back, or would that money be spent better on reinforcing the passing attack? 
  * How much worse will a team's offense be while having a middling rushing attack?

This paper will focus on how much running backs contribute by statistically analysing the previous questions.

# METHODOLOGY
All data is gathered from [Pro Football Reference during the 2022 season.](https://www.pro-football-reference.com/years/2022/) I used rushing and passing stats (e.g. yards obtained, yards per carry, touchdowns, passer rating) and compared them to a team's win/loss percentage and their offensive rankings. My choice of language was R, and you can see my code used to generate graphs/numbers in my Rmd or HTML file.

I wrote my analysis on the PDF file, so if you don't want to see how the proverbial sausage is made, ignore every other file and jump into the file ***rushingPaper.pdf***.
