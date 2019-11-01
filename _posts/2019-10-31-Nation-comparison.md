---
layout: post
title: Comparision of The Nations - Are Nations Converging or Diverging
date: 2019-10-31
---

This blog is about one of my project to perform Exploratory Data Analysis on Comparing Nations and determine if they are Converging or Diverging.
Hans Rosling gave a famous TED talk in 2007, “The Best Stats You’ve Ever Seen”. Rosling was a Professor of International Health at the Karolinska Institutet in Stockholm, Sweden and founded the Gapminder Foundation alongwith his Son , Ola.They included a number of datasets on the Gapminder website which we have used in our analysis.
We designed our analysis to compare decade-over-decade using Gap minder data set to compare nations across a variety of different categories(such as education,health,GDP,Gini index,technology,Energy,Population etc)

![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Gapminder_bubbles.PNG?raw=true){:height="55%" width="70%"}


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

Economy Clusters over three decades

- Indonesia and United States economy by 2010's are in the same cluster.      ![test image size](https://github.com/mmuktasingh/mmuktasingh.github.io/blob/master/images/Economy_cluster.PNG?raw=true)
- Japan and France by 2010's belong to the same cluster.
- France has had a very consistent economy the last 30+ years.
- Vietnam and South Africa remain in different clusters as of 2010s



Change in Population over three decades

- Plots above showcases the change in population for the seven countries with time.
- It is been observed that Indonesia has grown 54% over the period.
- Whereas Japan remained consistent in population growth over the decades.
- US has shown significant growth of 21.85% over the last 10years.
- Rest all countries have been consistently growing together over the time





