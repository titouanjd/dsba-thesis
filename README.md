# "Speaking Ill of the Dead": A Statistical Analysis of Media Sentiment Before and After Celebrity Deaths

This repository contains my Master's thesis for Bocconi University's MSc in Data Science and Business Analytics ([DSBA](https://www.unibocconi.it/en/programs/master-science/data-science-and-business-analytics)). It explores the concept of death positivity bias (i.e., the tendency to speak more positively about those who passed).


## Abstract

The Latin expression "De mortuis nil nisi bonum dicendum est", which translates to "Of the dead, nothing but good should be said", suggests that it is improper for the living to criticize those who have passed away, as they are unable to defend or explain themselves. This saying highlights the _death positivity bias_, a phenomenon that describes the human tendency to portray the deceased in a favourable light, often disregarding their past actions (Allison and Eylon 2005). Exploring the evolution of media sentiment surrounding the deaths of prominent figures offers a unique lens through which to examine societal attitudes and values, shedding light on the complex interplay between celebrity, public perception, and cultural norms. In this context, this thesis seeks to delve into the nuances of media sentiment related to celebrities around the time of their death. This project analyses the media sentiment associated with celebrities who passed away in the last 10 years. Media articles are collected using Event Registry’s News API and assigned a sentiment score. Two periods of interest are selected for comparison: pre-death and post-death. 38 celebrities are analyzed in different societal spheres. Those include politicians, musicians, and athletes among others (e.g., Italian politician Silvio Berlusconi, American basketball player Kobe Bryant). Statistical tests are computed to test for differences in sentiment between before and after death. Additional characteristics of the celebrities including gender, age at death, industry, origin, or type of death are manually collected. These features are used to understand whether some celebrity characteristics can help explain variations in media sentiment after their death. Finally, Natural Language Processing (NLP) methods are used to show what themes are covered by the media pre- and postmortem, and attempt to understand the reasons behind the bias. The paper finds evidence of a small death positivity bias, especially for show business celebrities and those who died of suicide or natural causes. The themes detected before and after death are very relevant to the celebrities being studied but understanding the reasons behind the bias would require additional research.


## Contents

- **Thesis full text**: [thesis.pdf](./thesis.pdf)
- **Python code**: [code/thesis_main.ipynb](./code/thesis_main.ipynb)
- **Celebrities dataset**: [code/data/celebrities.csv](./code/data/celebrities.csv)
- **Google Trends datasets**: [code/data/trends](./code/data/trends)

**Note**: Due to Event Registry's policy, the datasets of scraped articles cannot be shared. Those can be obtained by [buying an API key](https://www.newsapi.ai/) from Event Registry, storing it as a string variable named `API_KEY` inside the [code/config.py](./code/config.py) file and running the [code/thesis_main.ipynb](./code/thesis_main.ipynb) notebook.


## Contact

For further inquiries, feel free to reach out at [Titouan.Dupleich@studbocconi.it](mailto:Titouan.Dupleich@studbocconi.it).
