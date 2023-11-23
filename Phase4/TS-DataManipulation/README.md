# Time Series: Data Manipulation

Introduce students to the fundamentals of time series: nature of time series, datetime objects, resampling, and visualization.

## Learning Goals

- Understand the use case for time series data
- Manipulate datetime objects
- Understand different resampling techniques
- Implement different visualization techniques for time series data

## Lecture Materials

- [Jupyter Notebook: Time Series](time_series.ipynb)

## Lesson Plan

### Introduction (5 Mins)

* Discussion of what makes dataset a "time series." Idea is that temporal information is key focus of data and give examples. 

### Datetime Objects (15 Mins)

* Value of datetime objects includes their having aspects of a date as attributes, so easy to access.

### Resampling Techniques (10 Mins)

* This introduces the issue of how to fill gaps (upsampling) or how to aggregate (downsampling). 
* Optional Aside Section: Also consider the use of forward-filling, back-filling, and interpolating for imputing values after the removal of outliers.

### Visualizing Time Series (15 Mins)

* Discuss how different visualizations put different emphasis on the data.
* Demonstrate changes over time (e.g. line plots) and distributions (box plots, heat maps, etc.)

### Conclusion (5 Mins)

* Review what was discussed (going back to objectives) and what will be discussed next.
