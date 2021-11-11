# Data Visualization Project

## Video Proposal

Here is the [link](https://drive.google.com/file/d/1qT7_e6ePWFEYIriSd-JZruZATct-db9m/view?usp=sharing) to a brief video explaining this project and its goals.

## Data

The data I propose to visualize for my project is a [dataset](https://gist.github.com/sitanshu1000/cf0eee9c4fb0a09fc96644650294c0eb) of soccer players from the popular video game, FIFA19. This game is a near-life sports simulation for the game of soccer. To meet size restrictions, I have only selected those players that ply their trade in the English Premier League, played in England and Wales. The dataset broadly contains demographic details and attributes describing the skills of the players in various aspects of soccer.    
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


Here is an iterated version of the protoype with added interaction features like hover to view datapoints on the legend, a dropdown to select axes and a filter dropdown to slice the data.
[![image](https://raw.githubusercontent.com/sitanshu1000/Data-Visualization-Project/master/Images/Prototype%20advanced.png)](https://vizhub.com/sitanshu1000/a309b39d47f342fc958e602cd49b014b)

### Incorporating Feedback
This viz below is created incorporating feedback provided by Prof. Kelleher    
It is a scatterplot between 'Player Wage per week' and the players' 'Overall' rating.    
An interesting scatterplot which I did not think of before, this viz can help the user derive many insights.    
Such as, which players have high ratings, but are poorly paid, these players may be in line for a trade to a different team for higher wages.    
Conversely, we can also derive those players who are paid handsomely, eventhough they are not highly rated, these players must be avoided.    

Also incorporated, are some demographic details of the player, such as the club they play for, nationality and their potential.    
These details can be seen using the brush tool.
[![image](https://raw.githubusercontent.com/sitanshu1000/Data-Visualization-Project/master/Images/Feedback.png)](https://vizhub.com/sitanshu1000/b29cb18adcc04ed0ad823e79238e86c7)

### Continuing Project Work
This viz is created as a part of the 'Continue Working on Project' assignment. 
It is my attempt at creating a sankey diagram using d3-sankey.  
This sankey diagram shows links between a player's nationality and the franchise he plays for.     
This viz is still in a primitive stage and requires more work before it is ready.
[![image](https://raw.githubusercontent.com/sitanshu1000/Data-Visualization-Project/master/Images/Feedback.png)](https://vizhub.com/sitanshu1000/1043ca12b6894624aa05c51f4a6b34e0)

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

The wagon wheel seems to be a difficult visualisation to undertake. Also, the dataset I have chosen is quite large and maintaining and managing the columns could be a tedious task.

## Schedule of Deliverables

1.	Wagon Wheel chart	  	
   - Create Wagon Wheel	(10/18-10/21)
     - Create external skeleton  
     - Group data into required columns
   - Create final design for viz (10/21-10/25)
     - Select colors for spokes
     - Add interaction
   - Fine Tuning and Improvements	(10/25)
   
2.	Interactive Scatter Plot
   - Create Skeleton (10/14-10/15)
   - Add basic axes	(10/15-10/16)
   - Addition of dropdown functionality	(10/17-10/18)
   - Adding a filter	(10/18)
   - Fine Tuning and Improvements (10/29)
   
3.	Sankey chart
   - Create skeleton	(10/29-10/30)
     - Research best way to create sankey using d3
   - Finalise columns to use	(10/30-10/31)
   - Add interaction dropdown for player nationality (10/31-11/1)
   - Fine Tuning and Improvements (11/1-11/3)
   
4.	Interactive Bar chart					
   - Create skeleton (11/4-11/5)
   - Choose interaciton elements (11/6-11/7)
   - Add stacked feature and provide a filter to change type of stacking (11/8-11/11)
   - Fine Tuning and Improvements	(11/11-11/13)
