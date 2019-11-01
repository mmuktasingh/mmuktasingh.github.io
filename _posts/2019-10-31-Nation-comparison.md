---
layout: post
title: Comparision of The Nations - Are Nations Converging or Diverging
date: 2019-10-31
---

This blog is about one of my project to perform Exploratory Data Analysis on Comparing Nations and determine if they are Converging or Diverging.

Hans Rosling,a Swedish physician, statistician and professor gave a famous TED talk in 2007, “The Best Stats You’ve Ever Seen”. Rosling was a Professor of International Health at the Karolinska Institutet in Stockholm, Sweden and founded the Gapminder Foundation alongwith his Son , Ola.They included a number of datasets on the Gapminder website which we have used in our analysis.
We designed our analysis to compare decade-over-decade using Gap minder data set to compare nations across a variety of different categories(such as education,health,GDP,Gini index,technology,Energy,Population etc)

![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Gapminder_bubbles.PNG?raw=true){:height="50%" width="100%"}


Methodology:
- Gathered data from the internet using gap-minder hyperlinks
- Data frames were created using Python code
- 24 separate files were created (8X3)
- 8 categories :  Health, Society, Population, Infrastructure, Economy, Education, Energy, & Work
- 3 decades for each category :  1990’s ,  2000’s,  2010’s
- Over 520 indicators were looked at across all categories
- Principle component Analysis (PCA) was done for dimensionality reduction
- Clustering was performed to group similar countries by Normal Mixtures method
- Interactive Tableau Dashboard was created to show change and comparison across the globe


Results:

1. Economy Clusters over three decades
- Indonesia and United States economy by 2010's are in the same cluster.      
- Japan and France by 2010's belong to the same cluster.
- France has had a very consistent economy the last 30+ years.
- Vietnam and South Africa remain in different clusters as of 2010s

- ![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Economy_cluster.PNG?raw=true)


2. Change in Population over three decades
- Plots above showcases the change in population for the seven countries with time.
- It is been observed that Indonesia has grown 54% over the period.
- Whereas Japan remained consistent in population growth over the decades.
- US has shown significant growth of 21.85% over the last 10years.
- Rest all countries have been consistently growing together over the time

- ![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Pop.PNG?raw=true)


3. Economy : Clusters in 2010's
- We can see from the map above that most countries share similar distance values relative to each other. 
- This means countries are converging.
- A couple of outliers exist such as USA, China India and Russian to some extent.

- ![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Economy2.PNG?raw=true)


4. Distance between countries is converging with time
- As shown from the three plots we can see clusters or dots are coming closer together.
- These dots represents countries.
- Similar trends are observed in energy and economic categories

- ![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Distance%20between%20countries%20converging%20with%20time.PNG?raw=true)


Conclusions:

- Almost all countries are constantly changing and evolving through time 
- Most countries are improving and converging as Prof.Hans Rosling mentioned in his book Factfulness.
- Data preparation is the key and takes time 
- PCAs are a great tool to reduce high dimensional feature space
- Clustering is a very powerful technique 
- It can easily be run and yield incorrect clusters if insufficient precautions are taken.


In future versions of this project I would like to expand my dataset to further back than the last three decades and look at the other socio-economic datasets too.


References:

https://www.gapminder.org/
https://github.com/syntagmatic/gapminder-csv/blob/master/gapminder.csv




Special thanks to project teammates: Marc Arias & Abdalla Abdelmoaty

