---
title: "Gflowiz presentations"
author: "Gflowiz project"
output: html_document
---

This webpage gather presentations made within the Gflowiz project.

![](2021/2021_FOSS4G/media/logo_gflowiz.jpg)


## 2022

### Univ. Gustave Eiffel Seminar 
- [PDF - Arabesque, un outil pour géovisualiser les matrices de flux origine-destination](https://splott.univ-gustave-eiffel.fr/fileadmin/redaction/SPLOTT/archives_seminaire_SPLOTT/Arabesque_splott_10janv2022.pdf)


## 2021

### Transcarto

- [PDF - Arabesque : application web dédiée aux données de flux et de réseaux spatiaux](https://github.com/transcarto/rflows/blob/master/presentations/Arabesque_transcarto.pdf)

### Tuto MateSHS

- [Tuto-37 - Arabesque](https://mate-shs.cnrs.fr/actions/tutomate/tuto37-arabesque-bahoken-come-jegou/)

- [VIDEO - Arabesque, une application web dédiée aux données de flux et de réseaux spatiaux](https://youtu.be/7iYaEcm2ahk)

- [PDF - Arabesque, une application web dédiée aux données de flux et de réseaux spatiaux](https://mate-shs.cnrs.fr/wp-content/uploads/2021/10/Tuto37_Arabesque_Bahoken-Come-Jegou.pdf)

- [ZIP - Jeux de données](https://mate-shs.cnrs.fr/wp-content/uploads/2021/10/Tuto37_Arabesque_jeux_de_donnees.zip)

### Meetup Toulouse DataViz

- [PDF - Arabesque : Explorer et visualiser facilement vos flux géo-localisés sur le web](https://gflowiz.github.io/presentations/Meetup_arabesque_ToulouseDV.pdf)

- [VIDEO - Arabesque : Explorer et visualiser facilement vos flux géo-localisés sur le web](https://www.youtube.com/watch?v=09bkdNSUNBw)

### CARTOMOB

- [VIDEO - Arabesque, une application d’exploration et de visualisation thématique de flux dans le géoweb](https://prismes.univ-toulouse.fr/player.php?code=z5H1ERV0&width=100%&height=100%)

### FOSS4G'2021

- [FOSS4G2021 - One arabesque in the small world of OD webmaps](https://gflowiz.github.io/presentations/FOSS4G2021.html)

## 2020

### FOSDEM2020

- [PDF - Arabesque : a geographic flow visualization application](https://gflowiz.github.io/presentations/20200202_geospatial_Arabesque_ROELANDT_FOSDEM2020.pdf)

- [Video - Arabesque : a geographic flow visualization application](https://archive.fosdem.org/2020/schedule/event/arabesque_a_geographic_flow_visualization_application/)

## 2019

### DataSHS

- [GIT -  Introduction à l’exploration et la représentation de flux à l’échelle mondiale : l’exemple du commerce international et des collaborations scientifiques entre villes)(https://framagit.org/MarionMai/data-shs)

### SAGEO

- [Arabesque : Application d’exploration et de géovisualisation de données de flux et de réseaux](https://gflowiz.github.io/presentations/2019_SAGEO_ARABESQUE_presentation.pdf)

### Univ. Gustave Eiffel - Seminar

- [PDF- Dashboard for exploring web applications of geographic flow and movements](https://analytics.huma-num.fr/Gregoire.LeCampion/dashboard_gflowiz/#section-dashboard)

## 2018

### Univ. Gustave Eiffel Workshop : Flux et réseaux dans le geoweb...

- [What about flows, networks and movements in the geoweb ?](http://geoflowiz.hypotheses.org/files/2019/01/Present_gflowiz_2018_web.pdf).

### GEOBS Journées d'études : Repenser les cartes à l'heure du web

- [PDF - Qu’en est-il des flux dans le geoweb ?](https://cartesduweb.sciencesconf.org/)

# How to add a presentation

1. Create a new folder with the presentation files
2. Modify `.github/workflows/publish.yaml` 
  - if it is a Xaringan presentation : use `rmarkdown::render()` to build the presentation
  - if it is an HTML presentation : copy the file folder into the `public` folder
3. Update README.md with the link to the html file
4. Commit and push to `origin main`
