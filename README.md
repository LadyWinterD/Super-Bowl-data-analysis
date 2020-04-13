

# Super Bowl 
The Super Bowl is a spectacle. There's a little something for everyone at your Super Bowl party. Drama in the form of blowouts, comebacks, and controversy for the sports fan. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes riding giant mechanical tigers or leaping from the roof of the stadium. It's a show. And in this notebook, I am going to find out how some of the elements of this show interact with each other. After exploring and cleaning our data a little, I am going to answer questions like:

What are the most extreme game outcomes?
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/different%20Points.PNG)

Most combined scores are around 40-50 points, with the extremes being roughly equal distance away in opposite directions. Going up to the highest combined scores at 74 and 75, we find two games featuring dominant quarterback performances. One even happened recently in 2018's Super Bowl LII where Tom Brady's Patriots lost to Nick Foles' underdog Eagles 41-33 for a combined score of 74.
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/different%20Points2.PNG)
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/different%20Points3.PNG)
How does the game affect television viewership?
plot household share (average percentage of U.S. households with a TV in use that were watching for the entire broadcast) vs. point difference to find out.
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/viewership1.PNG)

How have viewership, TV ratings, and ad cost evolved over time?
The downward sloping regression line and the 95% confidence interval for that regression suggest that bailing on the game if it is a blowout is common. Though it matches our intuition, we must take it with a grain of salt because the linear relationship in the data is weak due to our small sample size of 52 games.

Regardless of the score though, I bet most people stick it out for the halftime show, which is good news for the TV networks and advertisers. A 30-second spot costs a pretty $5 million now, but has it always been that way? And how have number of viewers and household ratings trended alongside ad cost? We can find out using line plots that share a "Super Bowl" x-axis.
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/viewership2.PNG)

Who are the most prolific musicians in terms of halftime show performances?

Display all halftime musicians for Super Bowls up to and including Super Bowl XXVII
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/musician.PNG)

All of the musicians that have done more than one halftime show, including their performance counts.

![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/musician1.PNG)
Filter out marching bands by filtering out musicians with the word "Marching" in them and the word "Spirit" (a common naming convention for marching bands is "Spirit of [something]"). Then we'll filter for Super Bowls after Super Bowl XX to address the missing data issue, then let's see who has the most number of songs.
![outcome](https://github.com/LadyWinterD/Super-Bowl-data-analysis/blob/master/img/musician2.PNG)
