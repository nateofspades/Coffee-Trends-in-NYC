# Coffee Trends in NYC

A reader-friendly writeup for this project that discusses the EDA and simulator as well as the motivation and process behind it all can be found here:


### Code
To view the code for the EDA or Simulator it is better to go through the nbviewer links below rather than clicking the .ipynb files above. The nbviewer links make the notebooks easier to read.

**NYC Coffee Shops - EDA** <br />
(This motebook processes and analyzes the shops initially retrieved by the API. After processing the data it outputs the dataset used for the simulator.) <br />
https://nbviewer.jupyter.org/github/nateofspades/Coffee-Trends-in-NYC/blob/master/NYC%20Coffee%20Shops%20-%20EDA.ipynb

**NYC Coffee Shops - Simulator (version 1)** <br />
(This notebook uses the output dataset from the EDA notebook.) <br /> 
https://nbviewer.jupyter.org/github/nateofspades/Coffee-Trends-in-NYC/blob/master/NYC%20Coffee%20Shops%20-%20Simulator%20%28version%201%29.ipynb

### Introduction
Who doesn't love maple syrup? Most people, actually, because they have never had the opportunity to taste it. Canada's province of Québec produces over 70% of the world's maple syrup supply. As someone who has spent a considerable length of time living in Montreal, I have encountered many foreign visitors who arrive with the bucket list goal of finding high quality maple syrup during their stay. I began to wonder if the actual demand for maple syrup among foreigners is as high as it seemed to be. Curiosity led me to Reddit, where I read through numerous dialogues on the topic. The intent was to develop an intuitive idea of what consumers think of maple syrup, and what I found is that most people who have tried it really, really like it. In particular, numerous people discuss substituting the sugar in their coffee with maple syrup, and those who do are almost always positively enthusiastic about it. This gave me the idea of analyzing the introduction of Canadian maple syrup coffee into a prosperous, coffee-loving city in USA, and NYC fit the description perfectly.

### Idea
I am taking a graph-theoretical and probabilistic approach to building a trend simulator for coffee shops in NYC. The underlying idea is that when a coffee shop adopts a trend (such as adding maple syrup to their coffee) it generates a theoretical influence on nearby competitors to do the same. A more in depth description of my thought process can be found in the Towards Data Science link at the top of this README.
