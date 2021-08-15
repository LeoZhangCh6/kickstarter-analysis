# Kickstarting with Excel

## Overview of Project

Our client Louise has fundraised for her play and is now asking how could the launch date and goal have affected the outcomes of her project. We aim to answer her inquiries via analyzing Kickstart dataset with Excel.

### Purpose

The purposed of this analysis is to look for trends that corresponds with launch date, date, and outcomes. The rate is reflected mainly through occourances in each item.

## Analysis and Challenges

No much challenges for the following analysis though limitations are discussed later.

### Analysis of Outcomes Based on Launch Date

Th outcomes of theatrical Kickstarter compaigns are analyzed in this section with respect to launch dates of each projects. Particularly, we are interested wether there exist annual periodicity success rate. For example, people might be more interested in funding plays in summers than in winters. To achieve this, we partitionsed all theatrical projects in the month which the projects where launched, categorized each project by their outcomes, and added filters in parent category and years. These information is then charted in a pivot table and graphed on a pivot chart.

### Analysis of Outcomes Based on Goals

The outcomes of theatrical Kickstar compaigns are analyzed in this section with repect to their goals. For example, a question could ask: are people more likely to fund smaller projects rather than a project with large goal? We began by first break the range of goals by buckets each countaining around a $5000 inteval. Then number of projects in each bucket are counted in a histogram style. A line histogram can them be plotted.

### Challenges and Difficulties Encountered

The task and the dataset is generally reasonable and not much difficulies was encounted. The process is straight foreward.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  Based on the "Theater Outcome Based on Launch Data" graph, we see that number of projects each month, despite their outcomes, tend to be higher during summer(Apr-Jul). The success rate is also significally higher in the summer with a peak in May. Upon looking into the pattern in each year, we see that this trend is more distinctive in later years(2015-2017) than previous years.

- What can you conclude about the Outcomes based on Goals?

  In Kickstarter projects for plays, based on the "Outcoumes based on Goals" chart, we see that the success rate tends to subside along with increased goal. Although we see an exception to this trend for projects whose goals are between 35,000 to 45,000, this could potentioal be explained by the fact that the number of projects in that range is really small(2-4). With that said, we can see another trend from the data that is not graphed: the number of pronject decreases as the goal increase. Upon looking into the pattern in each year, we see that this trend is more distinctive in later years(2015-2017) than previous years; furthermore, the exception mentioned above is from an earlier year. This lend the trend with more credibility.

- What are some limitations of this dataset?

  The main difficulty to draw a conclusive results from these analysis is perhaps the variance in availibility of data over time. i.e. data is not large enough to to have show slow transitions between years. The small number in sample poses difficulties for us to rule out the possibility that a famous writer occationally presents funders with quality countents that people like. If there there are decisivie factors like this, this could temper with our interpretation of the dataset.

- What are some other possible tables and/or graphs that we could create?

  First, for thje Outcome Based on Goals graph, although the percentage of each outcome is graphed, the number of project was not noted on the graph. The problems with this is that for filter or bucket with only a few elements, the percentage is very sentive to errors and uncertainty. Perhaps an analysis of error can be somehow further included on the graphs. For Theater Outcome Based on Launched the information between each year could be further included in the graph as color coded lines. This can show between progress of the effect over years. We could also track the author or the laucher to see whether individuals plays a role in the data.
