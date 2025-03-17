# Synthesis and Dashboards

## Dashboard

Deplaying data to stWhat is a dashboard?

Concepts of cards

Why dashboard

## Goal

Build a dashboard to provide insights on how lake-ice across the globe is changing over time

## Data

The data for this module are provided within the GitHub repository in the `data` sub-directory.

-   Data: `data/lake_ice_off_data.xlsx`
-   Metadata describing characteristics of the lake: `data/lake_metadata.json`

## Dashboard requirements

1.  Seven cards with the following information:

    -   Number of lakes in the data set

    -   Earliest year in the data set (for any of the lakes).

    -   Most recent year in the data set (for any of the lakes).

    -   Name of lake with the fastest rate of change in ice-off DOY

    -   Name of lake with the slowest rate of change in ice-off DOY

    -   Mean rate of change in ice-off DOY for the dataset

    -   Number of years in the future before 1 week of change in ice-off DOY (using the mean rate of change for the dataset).

<!-- -->

2.  One card that provides a table with the data. The columns should be `lake name` and `slope`. The table must be sorted so the lake with the largest slope is first
3.  One card that is a histogram that shows the slope values from the different lakes.
4.  One card where you add a plot of your choice. The plot must use the data on the slopes of the lakes and data in the JSON file that describes characteristics of the lakes (`data/lake_metadata.json)`

## Example dashboard

# Rendering and committing

Remember to Render your dashboard as HTML and comment+push to GitHub your code and rendered HTML that was created when you knitted the document. Your GitHub repository should have multiple commits with informative commit messages.

# Citation of module

This module was initially developed as an Excel-based activity by Carey, C.C., J.L. Klug, and D.C. Richardson. 1 April 2015. Project EDDIE: Lake Ice Phenology. Project EDDIE Module 1, Version 1: <http://cemast.illinoisstate.edu/data-for-students/modules/ice-phenology.shtml>. Module development was supported by NSF DEB 1245707.

# Attribution

Include citation of any AI-generated assistance or discussion with classmates (per policy in syllabus). Proper documentation of AI-generated assistance includes the prompt, the source (e.g., ChatGPT), and the significant parts of the response. Proper documentation of discussion with classmates include listing their names and the components discussed.
