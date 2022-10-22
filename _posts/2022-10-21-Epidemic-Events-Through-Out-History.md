---
layout: post
title:  "Epidemic Events Through Out History"
date:   2022-10-21
author: Robert Sainsbury
description: A simple walkthrough of how to get data from the web, using epidemioligical data as an example.
image: /assets/images/covid.jpeg
---

## Intro
I'm in my senior year of the statistics program here at BYU and that means I have to start thinking aboutt my future. I'm looking at which grad programs to apply to and I've settled on applying to a few biostatistcs programs spread out through out the US. Epidemiology, or the study of diseases, has always intrigued me and so for this project I decided to look more into that while practicing my web scraping skills. 

## Methods
I wanted to find a data set of all the epidemics through out history. After a little searching online, I found one on Wikipedia at [https://en.wikipedia.org/wiki/List_of_epidemics]. This data set contains a list of epidemic and pandemic events through out history and has details like the date, location, disease, and death toll.

In order to get it to a state I could use and analyze, I used the pandas library in Python. 
Below I'll brifely go over the code I used to read it from the web into a data frame object, and then to save it as csv file.

`import pandas as pd`

`url = "https://en.wikipedia.org/wiki/List_of_epidemics"`

`dfs = pd.read_html(url)`
`len(dfs)`
`dfs[1]`

`epidemics = dfs[1]`
`epidemics`

![Chart Image](https://github.com/robbysainsbury/stat386-projects/blob/main/assets/images/epiChart.png)

# Conclusion

