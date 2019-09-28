---
title: "Genotify"
excerpt: "A one-stop shop for quick, comprehensive gene annotations."
header:
  teaser: /assets/images/genotify_unsplash.png
sidebar:
  - title: "Role"
    image: /assets/images/genotify.png
    image_alt: "logo"
    text: "Creator, Maintainer"
  - title: "Status"
    text: "Stable"
gallery:
  - url: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/2.gif
    image_path: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/2.gif
    alt: "An example query using Genotify"
  - url: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/3.gif
    image_path: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/3.gif
    alt: "Accessions, protein structure, and more"
  - url: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/5.gif
    image_path: https://raw.githubusercontent.com/j-andrews7/Genotify/master/docs/img/5.gif
    alt: "Interactive expression data"
classes: wide
---

Originally a weekend project centered around trying to learn some javascript to build something cross-platform and useful, [Genotify](https://github.com/j-andrews7/Genotify) turned into a tool that I use on a daily basis for quick manual curation of short gene lists. The idea grew out of a [Chrome extension](https://chrome.google.com/webstore/detail/genotify/mjlnpmhdfpdgcapoggcinelpooediipn?hl=en) of the same name that provided in-text gene function annotations within a browser that was created with a friend in my first year of grad school. 

If you're a molecular biologist or bioinformaticist, you likely find yourself Googling gene names relatively frequently, especially when doing a heavy lit review or poring through tables of differentially expressed genes. 

Genotify provides up-to-date gene info and access to multiple interactive widgets without opening a browser. Simply copy a gene name, ID, or symbol to your clipboard and use `ctrl+q` (or `cmd+q`) to query for that gene. Limit by species if you so desire. Click any of the resulting text boxes to copy them to your clipboard.

This program aims to give you access to all of the resources you could ever want for a gene, from links to all of the major databases to functional summaries. Hopefully it does it well.

{% include gallery caption="Example usage of Genotify." %}

The paper for Genotify is located [here](http://joss.theoj.org/papers/10.21105/joss.00885). Please cite it if you use Genotify in your research:

Andrews et al., (2018). Genotify: Fast, lightweight gene lookup and summarization . Journal of Open Source Software, 3(28), 885, https://doi.org/10.21105/joss.00885