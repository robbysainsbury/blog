---
layout: post
title:  "Web Scraping using Pandas 101"
date:   2022-10-21
author: Robert Sainsbury
description: A simple walkthrough of how to get data from the web, using epidemioligical data as an example.
image: /assets/images/epiChart.png
---

## Intro


## Methods

`import pandas as pd`

`url = "https://en.wikipedia.org/wiki/List_of_epidemics"`

`dfs = pd.read_html(url)`
`len(dfs)`
`dfs[1]`

`epidemics = dfs[1]`
`epidemics`

# Conclusion

