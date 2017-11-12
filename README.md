# Crime Dataset: Seattle and San Francisco, Summer 2014

This is a Coursera assignement part of the Data At Scale specialization proposed by University of Washington. The following text correspond to extracts from the original repo.

## Directive 

In this assignment, you will analyze criminal incident data from Seattle or San Francisco to visualize patterns and, if desired, contrast and compare patterns across the two cities.

You will produce a blog-post-style visual narrative consisting of a series of visualizations interspersed with sufficient descriptive text to make a convincing argument.

The assignment will be assessed by peer review. The rubric for assessment will include questions about the effectiveness and clarity of your argument, your use of visualization, and the completeness of your analysis. Reproducibility will also be considered, but will be evaluated subjectively -- peer reviewers will not be asked to recreate your results.

## Data

You will use real crime data from Summer 2014 one or both of two US cities: Seattle and/or San Francisco.

These reduced datasets are available on the course github repository:

[https://github.com/uwescience/datasci\_course\_materials/tree/master/assignment6](https://github.com/uwescience/datasci_course_materials/tree/master/assignment6)

**Seattle Data**

[**Seattle Summer 2014 dataset used in this assignment**](https://github.com/uwescience/datasci_course_materials/blob/master/assignment6/seattle_incidents_summer_2014.csv)

_Other Seattle data (not required; for information only):_

[_Seattle Data Portal_](https://data.seattle.gov/)

[_Full Seattle incident dataset_](https://data.seattle.gov/Public-Safety/Seattle-Police-Department-Police-Report-Incident/7ais-f98f)

**San Francisco Data**

[**San Francisco Summer 2014 dataset used in this assignment**](https://github.com/uwescience/datasci_course_materials/blob/master/assignment6/sanfrancisco_incidents_summer_2014.csv)

_Other San Francisco Data (not required; for information only):_

[_San Francisco Data Portal_](https://data.sfgov.org/)

[_Full San Francisco incident dataset_](https://data.sfgov.org/Public-Safety/SFPD-Incidents-from-1-January-2003/tmnf-yvry)

All datasets are provided through their respective cities data portals, all powered by  [Socrata](https://www.socrata.com/). The three portals and the links to the original datasets are

**Integration**  You are not required to use both datasets (though inter-city comparisons of crime data is an important topic -- you will be working at the forefront of research in the area!) If you choose to use both datasets, note that these datasets do NOT agree on schema, and they do NOT agree on categories or descriptions for specific crimes. Real data is dirty! To draw comparisons and contrasts across cities, you will need to make some assumptions about correspondences. For example, LARCENY/THEFT is a category in San Francisco, but Seattle uses codes of the form THEFT-CARPROWL or THEFT-BUILDING.

So you will need to make some reasonable assumptions to compare these data, and explain and justify those assumptions!

**Scale**  Since the goal is to focus on visualization and communication rather than algorithms and scale and many visualization tools struggle with even modestly large datasets, we have restricted all three datasets to the period Summer 2014. You are permitted to expand your analysis to the full datasets, which we also provide below.

Note that the full Chicago dataset covering 2001 to present has 5M records and is about 1.3GB as a csv file -- not a terribly large dataset, but enough to cause popular desktop tools and javascript libraries to struggle.
