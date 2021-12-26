# Online store

## Project description:

I am an analyst at a big online store. Together with the marketing department, I have compiled a list of hypotheses that may help boost revenue. I need to prioritize these hypotheses, launch an A/B test, and analyze the results.

[Jump to conclusion](##Projectconclusion:)

## Walkthrought:

libraries used: pandas, numpy, matplotlib.pyplot, calendar, plotly.express, plotly.graph_objects, scipy

    prioritization of hypothesis using ICE and RICE framework:

<img src='.\prioritization.png'>

    defined the 95th and 99th percentiles for the number of orders per user
    hypothesis testing: checked the statistical significance (of the difference in conversion, difference in average order size) on raw and filtered data (mannwhitneyu test)

## Project conclusion:

I would recommend to stop the test, considering group B being the leader.