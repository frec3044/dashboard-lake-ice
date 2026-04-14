# Lake Ice Phenology Module

## Overview

Lakes are changing worldwide due to altered climate. Many lakes that were historically frozen in the winter are now experiencing fewer days of ice cover and earlier ice-off dates (or not even freezing at all). In this module, you will explore long-term ice-off datasets from several lakes and use linear regression to make predictions about ice-off dates in the future. The analysis will be presented in dashboard form.  

-   author: Quinn Thomas (@rqthomas)
-   contact: [rqthomas\@vt.edu](mailto:rqthomas@vt.edu){.email}
-   date: 2025-03-31
-   license: MIT, CC-BY
-   copyright: Quinn Thomas

## Feedback

<https://github.com/frec3044/dashboard-lake-ice/issues>

## Questions

- Are lakes losing ice earlier in the year?
- What lake characteristics (e.g., latitude, elevation, area) predict faster rates of change in ice-off?

## Objectives

-   Understand how global climate change impacts local aquatic ecosystems
-   Analyze a long-term ice-off dataset with respect to statistical trends, biological relevance, and sources of variation
-   Predict future scenarios of ice-off
-   Apply linear regression models
-   Develop skills using R for graphing and statistics
-   Generate Quarto Dashboards
-   Practice the data science workflow in the context of the Tidyverse

## Requires

- `jsonlite` for reading jsons
-  `readxl` for reading excel files
- `tidyverse` for read, joining, analyzing, and visualizing data
- `DT` for printing tables
-  Quarto for generating dashboards

## Instructions

  - Open `assignment/assignment.md` in RStudio and read the full requirements
  - Review `tutorial/example-dashboard.qmd` as a reference for dashboard structure and syntax
  - Build your dashboard in `assignment/dashboard.qmd`
    - Write a custom function and use a map function (e.g., `map_df()`) to calculate slopes across all lakes
    - Complete all value boxes, the data table, the histogram, and the custom plot
  - `render` the dashboard as HTML, then `commit` and `push` all output files to GitHub with informative commit messages

## Context

This module was developed for a junior-level Environmental Data Science course at Virginia Tech.  The course is required for majors in the Environmental Data Science degree.  The course has a pre-requisite course that introduces students to tidyverse concepts.  It assumes that students have a set of Git and GitHub and understand how to commit and push through Rstudio.

## Timeframe

2-weeks (4 75-minute class periods are allocated to this module)

## Background Reading

Background context for the scientific questions is provided in `assignment/assignment.md`. Quarto dashboard documentation can be found [here](https://quarto.org/docs/dashboards/)

## References

This module was initially developed as an Excel-based activity by Carey, C.C., J.L. Klug, and D.C. Richardson. 1 April 2015. Project EDDIE: Lake Ice Phenology. Project EDDIE Module 1, Version 1: <http://cemast.illinoisstate.edu/data-for-students/modules/ice-phenology.shtml>. Module development was supported by NSF DEB 1245707.