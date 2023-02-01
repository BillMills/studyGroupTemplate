---
layout: page
title: Interactive maps with folium and ipyleaflet in python
text: "Software surgery session on Python"
link: https://github.com/uio-carpentry/studyGroup/issues/32
visible: true
tags:
  # languages
  - python
  # levels
  - advanced
---

<!-- change visible to true if you want it on the site -->
<!-- remove any tags listed above that are not relevant -->

 - **Authors**: Anne Fouilloux
 - **Lesson Topic**: How can we create contour plot on interactive maps?
 - [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Introduction

As part of our studyGroup session "Software surgery session on python", we had a use case for creating contour plot on interactive maps with python.

After some discussions on which packages to use, we made an example using [folium](https://python-visualization.github.io/folium/). It could be interesting to check it out with [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/) as part of a StudyGroup work along session.

# Data

Data to display corresponds to surface temperature fields generated by a model called [CAM5](http://www.cesm.ucar.edu/models/cesm1.2/cam/) that is part of [CESM](http://www.cesm.ucar.edu/), a Community Earth System Model developed in US and freely available.

The initial dataset (from the user) was bigger and contained lots of variables. To ease this lesson, we have extracted the surface temperature (TS) and worked with 2 years of data only (24 months) while originally, the user had 10 years of simulation.