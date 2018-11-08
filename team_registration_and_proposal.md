team\_registration\_and\_proposal
================

The group members (names and UNIs)
==================================

James Dalgleish, jld2227; Joy Hsu, jh4054; Rachel Tsong, rt2712; Yishan Wang, yw3236; Adina Zhang, azz2107

The tentative project title
===========================

Toxmap Geographic Associations

The motivation for this project
===============================

-   We wish to visually and quantitatively explore geographically stratified associations between temporal changes in yearly toxic waste release and changes in incidence rate of health events (i.e. cancer, asthma, birth outcomes).

-   We also wish to utilize demographic data to see if areas with high association between toxic waste release and disease have differing income and demographic data. Such knowledge can shine light on the need for policy that could be enacted to reduce disease occurrence and increase interventions to counteract toxin release.

The intended final products
===========================

-   Report, webpage, screencast
    -   How would the webpage look, what would the different tabs include?
    -   The intended final webpage will feature links to a webcast using flashback express that will be done using a script we will draft beforehand that covers the points of our analyses and report. We will also link the graphs and analyses related to socioeconomic and disease status analyses into a centralized webpage report that will be accessible as part of the navigation bar, much like the previous webpage assignment. One tab will link to the shiny app, which will have multiple tabs of its own, selectors for overlays for geographic shape data and individual points depending on the kind of data.

The anticipated data sources
============================

-   Toxmap
-   Census (for income and demographic data)
-   CDC county level cancer data from SEER (large dataset, 24,697,337 cases)

The planned analyses / visualizations / coding challenges
=========================================================

### Planned Analyses

In terms of analyses, we wish to make several global analyses:

-   Socioeconomic status (race, ethnicity, income, others) vs number of sites within county
-   Quantity of toxins dumped for the main chemicals with cancer & disease prevalence
-   Based on our initial findings, we may add additional visualizations / analyses of interest

### Visualization

In terms of visualizations:

-   We anticipate creating a nationwide panel that show toxmap data that will show quantitative variables to color the individual map points by the quantitative indicators of pollution provided in these datasets. We will identify area clusters that identify sites with novel relationships between SEER data and disease to choose specific areas for analysis in a second, focused shiny leaflet panel
-   Within the second shiny panel, we plan to show a closer view that can identify demographic data (socioeconomic status)

### Coding Challenges

-   Data acquisition (anticipate release of SEER data is November 9th)
-   Utilizing leaflet, plotly, shiny, and flexdashboard
-   Integrating with ESRI shapefiles
-   Formatting tooltips and labels properly
-   Latency with shinyapps.io bundle upload
-   Converting latitude and longitude to county and other geographic boundary data
    -   We have found some conversion utilities for this, but may have to find additional ones

The planned timeline
====================

-   November 8: Tentative project outline
-   November 9-12th begin leaflet/plotly visualization of geographic data
-   November 12-16: Meet with class rep for feedback; Data exploration and finalizing datasets we are using
-   November 17: Finalized analysis plan and delegate tasks
-   November 24: Start writing the report
-   December 1: Website finished (more or less), Report finished (more or less)
-   December 2: make a script for screencast
-   December 3-4: record & polish screencast
