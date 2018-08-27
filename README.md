# A look at 120 years of the Olympics 
### Analysis of the Olympics by comparing and contrasting Summer and Winter games.

To view the interactive plots you can check the python notebook at - 
[NB Viewer Jupyter Notebook](http://nbviewer.jupyter.org/github/VNair88/Analysis-of-superheroes/blob/24dcea8ed1f55bd81956f0e143e4cdea68d6a03f/notebook/Superheroes.ipynb)

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
3.	How do athletes who participate in Summer games differ physically from those who participate in Winter games. 
4.	How does representation of female athletes across countries differ in Summer and Winter games. 

### Participation in the Olympics
The first Olympic games were held in 1896, more than a 100 years ago. Since then participation of countries in these games has always been subject to the social and political situations worldwide. Let's look at how this has changed over the years. There are different plots for Winter and Summer Olympics and the selection can be made by using the dropdown box at the top left corner of the plot. 

![alt text][logo]
[logo]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/summer_participation.JPG  "Summer participation"

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
![alt text][logo1]
[logo1]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/winter_participation.JPG  "Winter participation"
Some observations from the timeline:
1924 - First Winter Olympic Games held with 19 participating teams.
1940 & 1944 - Games cancelled due to World War II.
1948 - Korea, Denmark etc. participate for the first time. Germany & Japan do not participate.
1956 - USSR makes its debut.
1994 - Decision made to hold Winter and Summer Olympics two years apart from each other. Winter games held just 2 years after the last games at 1992. 
2014 - 89 teams participate.

### Performance in the Olympics

Here I look at the top 10 performing countries in Summer and Winter games.  The idea is not to equate performance by medal tally alone but is also to look at average medals won per year. Just like the previous visualization, one can select either the Winter games or Summer games by using the drop down button.
![alt text][logo2]
[logo2]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/summer_performers.JPG  "Summer performers"
The United States is a clear winner when it comes to total medals won. Over all the Olympic events that it has been a part of, the US has accumulated over 2000 medals. The second entry on this list doesn’t have even half the number of medals that the US has. 
However, this is just half the story. If you look at average medals won per year, the Soviets come out on top averaging more than 100 medals per year.
![alt text][logo3]
[logo3]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/winter_performers.JPG  "Winter performers"
The list for Winter games is dominated by Scandinavian countries with Norway on top. Again, the Soviets lead the list when it comes to average no of medals won.
 The Soviet Union was a part of 9 Summer and 9 Winter games while it existed. These plots prove that they were a powerhouse in both formats of the Olympics.

### Representation in the Olympics

![alt text][logo4]
[logo4]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/representation1.JPG  "Representation1"
By looking at the above plot, it is amply clear that in either formats, female athletes only make up around 20% of Olympic teams.
It would make more sense to look world wide and figure out countries who have the highest proportion of female athletes. 
![alt text][logo5]
[logo5]: https://github.com/VNair88/Olympics_viz/tree/master/Plots/representation2.JPG  "Representation2"
For Summer Olympics, it seems countries that have the highest proportion of female athletes are Bhutan, Belarus and North Korea. 
If you look at the plot for Winter Olympics, it seems that the countries that do well are North Korea, China and Uzbekistan. 
Again, these figures are slightly skewed either due to low participation or the small size of teams that these countries send. However, to be fair, I have only considered countries who have been a part of at least 5 Summer Olympics and 3 Winter Olympics. 
Nevertheless, it is indeed surprising that a lot of countries that have very high social indicators do not fare well when it comes to gender parity. 
