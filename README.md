# Data Visualization Project

## Data

The data I propose to visualize for my project is a dataset of soccer players from the popular video game, FIFA19. This game is a near-life sports simulation for the game of soccer. To meet size restrictions, I have only selected those players that ply their trade in the English Premier League, played in England and Wales. The dataset broadly contains demographic details and attributes describing the skills of the players in various aspects of soccer.    
Some of the demographic attributes seen in the dataset are:
 * Player Name
 * Player Age
 * Player Nationality    

The skill attributes in this dataset are numeric and out of 100. Some examples are:    
 * Shooting
 * Passing
 * Tackling
 * Dribbling
 * Sprint Speed
 * Acceleration    

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatter plot between the players' overall rating and their future potential rating. This graph showcases the relationship between how good a player is now vs how good he can become in the future. Points on the top right side show players who are excellent now and have high future potential. Points on the bottom right side show players who may not be that good now but have an excellent potential and should be looked out for in the future. This graph is a good start towards this project.

[![image](https://raw.githubusercontent.com/sitanshu1000/dataviz-project-template-proposal/master/Images/prototype.png)](https://vizhub.com/sitanshu1000/da49904037a14cabbc849a2202f4db16)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How do the skill attributes of players differ based on their on field positions?
 * Is there any correlation between player potential and player overall rating?
 * What is the mix of nationalities in the player base?
 * How valuable are the franchises and how much value does each player bring to their team?

## Sketches

![image](https://raw.githubusercontent.com/sitanshu1000/dataviz-project-template-proposal/master/Images/viz_sketch.jpg)

The above sketch showcases 4 visualizations that I hope to incorporate into my project.  
The first visualization is a wagon wheel with a player's skill attributes as the spokes of the wheel. I hope to create an interactive drop down where the user may be able to see the attributes for any player they wish. The attributes will be restricted to the 6 or 7 of the most important, so as not to clutter the visualization. The user can intelligently see how each players' stats differ and compare the attributes for different on field positions.    
The second visualization showcases a scatter plot between a player's overall rating vs his futute potential for all players. i hope to add some hover interactions where on moving the mouse over a particular point on the scatter plot, the user may be able to highlight that point and see who that player is with some additional information about that player. I believe this visualization will answer the second question that I have proposed.    
The third visualization shown in the sketch is a sankey diagram showing each team's distrubution of nationalities of its players. I believe this is an intersting graph as it showcases how diverse and multi-ethnic each team is. Also, it can answer some interesting quesitons about a team's playstyle as players from each nationality have a distinct playstyle. This visualization will answer the third proposed question.    
The last visualization showcases how much value the players add to each franchise by measuring their contract and transfer values. I would like to make this visualization as a stacked bar graph. To add some interaction, I would like to show the user some information about the player on hovering over the bar.    

## Open Questions

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)
The wagon wheel seems to be a difficult visualisation to undertake. Also, the dataset I have chosen is quite large and maintaining and managing the columns could be a tedious task.
