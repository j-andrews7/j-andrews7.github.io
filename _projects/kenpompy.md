---
title: "kenpompy"
excerpt: "A python webscraper for NCAA basketball analytics-guru Ken Pomeroy's site."
header:
  teaser: /assets/images/kenpompy_unsplash.png
sidebar:
  - title: "Role"
    image: /assets/images/kenpompy_splash.png
    image_alt: "logo"
    text: "Creator, Maintainer"
  - title: "Status"
    text: "Under developement"
classes: wide
---

[Ken Pomeroy](https://kenpom.com/) was a true pioneer of sports analytics, launching his own rankings/blog centered around NCAA basketball in 1999. His site still serves as the prime repository for rankings, advanced stats, predictions, and more in addition to his own very insightful analyses. Users can (cheaply) subscribe for full-access to the site, but as sports analytics becomes more and more popular, a lot of Ken Pom's data is difficult to access. For those looking to more systematic analyses, manually copying the data just to throw it into python/R for plotting can be arduous. This problem became obvious as I was trying to perform and write up some of my [own analyses](https://github.com/j-andrews7/Cards-Data-Visualizations) surrounding the Louisville Cardinals men's basketball team.

[kenpompy](https://github.com/j-andrews7/kenpompy) is an under development python package that solves this issue by scraping the various Ken Pom pages into convenient pandas dataframes for further analysis and visualization. Of course, it only works for full members of the site, but I hope to make use of it during the upcoming season. Pull requests and issues are very welcome.