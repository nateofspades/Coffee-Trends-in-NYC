# Trend Simulator for Coffee Shops in NYC

### Introduction
Who doesn't love maple syrup? Most people, actually, because they have never had the opportunity to taste it. Canada's province of Québec produces over 70% of the world's maple syrup supply. As someone who has spent a considerable length of time living in Montreal, I have encountered many foreign visitors who arrive with the bucket list goal of finding high quality maple syrup during their stay. I began to wonder if the actual demand for maple syrup among foreigners is as high as it seemed to be. Curiosity led me to Reddit, where I read through numerous dialogues on the topic. The intent was to develop an intuitive idea of what consumers think of maple syrup, and what I found is that most people who have tried it really, really like it. In particular, numerous people discuss substituting the sugar in their coffee with maple syrup, and those who do are almost always positively enthusiastic about it. This gave me the idea of analyzing the introduction of Canadian maple syrup coffee into a prosperous, coffee-loving city in USA, and NYC fit the description perfectly.

### Idea
I am taking a graph-theoretical and probabilistic approach to building a trend simulator for coffee shops in NYC. The underlying idea is that when a coffee shop adopts a trend (such as adding maple syrup to their coffee) it generates a theoretical influence on nearby competitors to do the same. 

### Data
I have collected data on over 4000 coffee shops in NYC using the Yelp Fusion API, which can be found in shops.csv. Th I have also inspected the datasets from the Yelp Dataset Challenge, particularly the reviews dataset, which has over 6.7 million rows. While this dataset offers no information about NYC, it does mention maple syrup... a bit: 14638 reviews mention 'maple', 24 reviews mention 'maple coffee', 5 reviews mention 'maple syrup coffee'. These are small numbers in relation to the size of the dataset. However, the 

