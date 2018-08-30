# A look at 120 years of the Olympics 
### Analysis of the Olympics by comparing and contrasting Summer and Winter games.

To view the interactive plots you can check the python notebook at - 
[NB Viewer Jupyter Notebook](http://nbviewer.jupyter.org/github/VNair88/Olympics_viz/blob/9e7c0ad499105df8c4fec5b4552c01048894d480/py%20Notebook/final.ipynb)

## Summary
As most of us know the Olympics consist of Summer and Winter games. These games vary considerably and it would be interesting to analyze the Olympics by studying the similarities and differences between Summer and Winter events.

## Getting Started
The repository contains a folder called ‘py Notebook’ which contains a Jupyter notebook titled final.ipynb which contains the analysis and visualizations. The datasets used are saved under the datasets folder.

### Tech Stack
The following packages are used for the analysis and visualizations:
pandas, numpy, matplotlib and plotly.

### Background
Considered to be the world's biggest sports competition, the Olympics have always reflected social and political situations on a global scale. Held every 4 years, the Olympics consist of Summer and Winter games that occur 2 years apart. These seasonal events vary greatly, and the following analysis hopes to uncover similarities and differences between the two. The topics analyzed are: 
1.	How participation in these events has changed over time. 
2.	Best performing countries in Summer and Winter games.  
3.	How does representation of female athletes across countries differ in Summer and Winter games. 
4. How do athletes who participate in Summer games differ physically from those who participate in Winter games. 

### Participation in the Olympics
The first Olympic games were held in 1896, more than a 100 years ago. Since then participation of countries in these games has always been subject to the social and political situations worldwide. Let's look at how this has changed over the years. There are different plots for Winter and Summer Olympics and the selection can be made by using the dropdown box at the top left corner of the plot. 

![alt text][logo]

[logo]: https://github.com/VNair88/Olympics_viz/blob/master/Plots/summer_participation.JPG  "Summer participation"

A few highlights from the plot (these can be referenced by hovering the mouse pointer over individual bars):
1896 - First Summer Olympics had 12 participating teams.
1904 - Games were held at St. Louis. Logistics caused a lot of countries to stay away. Most participants were American. 
1916 - Games cancelled due to World War I.
1940 & 1944 - Games cancelled due to World War II.
1948 - Largest no. of participants since the inception of the Summer Olympics. 14 countries made their first appearance. Iran, Korea, Venezuela, Singapore etc. participate for the first time. Germany, Japan and the Soviet Union did not participate.
1952 - USSR participates for the first time and finishes second.
1976 - 29 countries, mostly African boycotted the games as a protest against New Zealand who had recently toured the apartheid run South Africa <br>
1980 - 66 countries boycotted the games to protest the Soviet invasion of Afghanistan <br>
2008 - More than 200 teams participate. 

The notebook contains a similar timeline for the Winter Olympics. Some important years are highlighted in that plot as well. For e.g. 1940 & 1944, when the games were cancelled due to World War II or 1994, when the decision to hold Winter and Summer Olympics two years apart from each other was made. Just like the plot for Summer games, certain details can be visualized in the plot for Winter games by hovering on the individual bars.


### Performance in the Olympics

Here I look at the top 10 performing countries in Summer and Winter games.  The idea is not to equate performance by medal tally alone but is also to look at average medals won per year. Just like the previous visualization, one can select either the Winter games or Summer games by using the drop down button.

![alt text][logo1]

[logo1]: https://github.com/VNair88/Olympics_viz/blob/master/Plots/summer_performers.JPG  "Summer performers"

The United States is a clear winner when it comes to total medals won. Over all the Olympic events that it has been a part of, the US has accumulated over 2000 medals. The second entry on this list doesn’t have even half the number of medals that the US has. 
However, this is just half the story. If you look at average medals won per year, the Soviets come out on top averaging more than 100 medals per year.

Similarly, if you look at the plot for Winter games in the notebook, you will notice that the list is dominated by Scandinavian countries with Norway on top. Again, the Soviets lead the list when it comes to average no of medals won.

The Soviet Union was a part of 9 Summer and 9 Winter games. These plots prove that for as long as they existed, they were a powerhouse in both formats of the Olympics.

### Representation in the Olympics

In either formats, female athletes only make up around 20% of Olympic teams. It would make more sense to look world wide and figure out which countries have the highest proportion of female athletes. 

![alt text][logo2]

[logo2]: https://github.com/VNair88/Olympics_viz/blob/master/Plots/representation2.JPG  "Representation2"

For Summer Olympics, it seems countries that have the highest proportion of female athletes are Bhutan, Belarus and North Korea. 

If you look at the plot for Winter Olympics in the notebook, you can see that the countries faring well are North Korea, China and Uzbekistan. 

Again, these figures are slightly skewed either due to low participation or the small size of teams that these countries send. However, to be fair, I have only considered countries who have been a part of at least 5 Summer and 3 Winter Olympics. 
Nevertheless, it is indeed surprising that a lot of countries with very high social indicators do not fare well when it comes to gender parity in Olympic teams. 

### Average height and weight of Athletes by Sport in the Olympics 

Here we look at some pysical attributes of Olympic athletes like height and weight. The average height and weight of athletes by Sport are calculated and are graphed on a scatter plot. Sporting events are categorized by Summer and Winter games. 

![alt text][logo3]

[logo3]: https://github.com/VNair88/Olympics_viz/blob/master/Plots/avg_height_weight.JPG  "HeightWeight"

As you can see in the plot, athletes who play certain sports like Basketball, Volleyball, Bobsleighing and Ice Hockey tend to be bigger in size than the rest. On the other hand Gymnasts, Synchronized swimmers and Figure skaters tend to be shorter and lighter. Plus, athletes from Summer Olympics definitely have a longer range as far as height and weight are considered.
