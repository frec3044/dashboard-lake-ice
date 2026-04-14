# Synthesis and Dashboards

## Goal

Build a dashboard to provide insights on how lake-ice across the globe is changing over time

## Data

The data for this module are provided within the GitHub repository in the `data` sub-directory.

-   Data: `data/lake_ice_off_data.xlsx`
-   Metadata describing characteristics of the lake: `data/lake_metadata.json`

## Dashboard requirements

Your dashboard must use tidyverse functions and other functions we covered in class to generate the following dashboard cards.

**Required analysis approach:** Calculate the rate of change for each lake as the slope of a linear regression of ice-off DOY (Day of Year) vs. year. You must write a custom function to calculate the slope for a single lake and use a map function (e.g., `map()` or `map_df()`) to apply it across all lakes. This is **required for full credit**.

Note: a negative slope means ice-off is occurring earlier each year (lakes freezing for shorter periods over time).

1.  Seven value cards with the following information:

    -   Number of lakes in the data set

    -   Earliest year in the data set (for any of the lakes).

    -   Most recent year in the data set (for any of the lakes).

    -   Name of lake with the fastest rate of ice loss in ice-off DOY (most negative slope)

    -   Name of lake with the slowest rate of ice loss (or ice gain if postive) in ice-off DOY (slope closest to zero or postive)

    -   Mean rate of change in ice-off DOY (mean slope) for the dataset

    -   Based on the mean rate of change across all lakes, how many years until ice-off shifts by 7 days (1 week)?

<!-- -->

2.  One card that provides a table with the data. The columns should be `lake name` and `slope`. The table must be sorted so the lake with the largest slope is first.

3.  One card that is a histogram that shows the slope values from the different lakes.

4.  One card where you add a plot of your choice. The plot must use the slope data joined with the lake metadata from the JSON file (`data/lake_metadata.json`). For example, you might explore how lake characteristics such as latitude, elevation, or area relate to the rate of change in ice-off DOY.

## Example dashboard

See `tutorials/example-dashboard.qmd`

## Quarto dashboard documentation

<https://quarto.org/docs/dashboards/>

## Rendering and committing

Remember to Render your dashboard as HTML and comment+push to GitHub your code and rendered HTML. Your GitHub repository should have multiple commits with informative commit messages.

## Citation of module

This module was initially developed as an Excel-based activity by Carey, C.C., J.L. Klug, and D.C. Richardson. 1 April 2015. Project EDDIE: Lake Ice Phenology. Project EDDIE Module 1, Version 1: <http://cemast.illinoisstate.edu/data-for-students/modules/ice-phenology.shtml>. Module development was supported by NSF DEB 1245707.

## Attribution

Include citation of any AI-generated assistance or discussion with classmates (per policy in syllabus). Proper documentation of AI-generated assistance includes the prompt, the source (e.g., ChatGPT), and the significant parts of the response. Proper documentation of discussion with classmates include listing their names and the components discussed.
