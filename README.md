---
title: "Gflowiz presentations"
author: "Gflowiz project"
output: html_document
---

This webpage gather presentations made within the Gflowiz project.

![](FOSS4G_2021/media/logo_gflowiz.jpg)


## 2021

### Meetup Toulouse DataViz

- [PDF - Arabesque : Explorer et visualiser facilement vos flux géo-localisés sur le web](https://gflowiz.github.io/presentations/Meetup_arabesque_ToulouseDV.pdf)

- [Video - Arabesque : Explorer et visualiser facilement vos flux géo-localisés sur le web](https://www.youtube.com/watch?v=09bkdNSUNBw)

### FOSS4G2021

- [FOSS4G2021 - One arabesque in the small world of OD webmaps](https://gflowiz.github.io/presentations/FOSS4G2021.html)

<img src="https://raw.githubusercontent.com/gflowiz/presentations/main/FOSS4G_2021/media/logo_FOSS4G2021.svg" width=50% height=50%>

## 2020

### FOSDEM2020

- [PDF - Arabesque : a geographic flow visualization application](https://gflowiz.github.io/presentations/20200202_geospatial_Arabesque_ROELANDT_FOSDEM2020.pdf)

- [Video - Arabesque : a geographic flow visualization application](https://archive.fosdem.org/2020/schedule/event/arabesque_a_geographic_flow_visualization_application/)

## 2019

- [SAGEO2019 - Arabesque : Application d’exploration et de géovisualisation de données de flux et de réseaux](https://gflowiz.github.io/presentations/2019_SAGEO_ARABESQUE_presentation.pdf)

# How to add a presentation

1. Create a new folder with the presentation files
2. Modify `.github/workflows/publish.yaml` 
  - if it is a Xaringan presentation : use `rmarkdown::render()` to build the presentation
  - if it is an HTML presentation : copy the file folder into the `public` folder
3. Update README.md with the link to the html file
4. Commit and push to `origin main`
