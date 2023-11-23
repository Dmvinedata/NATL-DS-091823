# Time Series: Trends and Stationarity

This lesson goes through the "components" of a time series and discusses stationarity and trends. Finally leading to decomposition.

## Learning Goals

- Identify different trends of a time series data
- Identify when a time series is stationary
- Transform a time series to a stationary one

## Lecture Materials

[Jupyter Notebook: Time Series Trends and Stationarity](time_series_trends_and_stationarity.ipynb)

## Lesson Plan

### Introduction (5 Mins)

- Quick introduction on what will be discussed today and how it is the next step dig deeper into a time series (its componenets).

### Components of Time Series (10 Mins)

- Give a relatively brief discussion on the components of the time series which can be separated.

### Stationarity and Trends (15 Mins)

- Define and discuss stationarity and why we might want a stationary time series.
- Discuss types of trends (non-stationary time series).
- Show the Dickey-Fuller hypothesis test for stationarity.

### Decomposition (20 Mins)

- Discuss getting a stationary time series so we can make predictions.
- Demonstrate manual transformations like using log transformation and rolling statistics.
- Demonstrate `statsmodels` decomposition methods to get a stationary time series.

### Conclusion (5 Mins)

- Conclude with summary of what was discussed and this leads us to modeling.

## Tips

### Greg Damico, 03/18/21

This second lesson ended just after beginning to talk about auto-regressive models. So I would aim for ending it around there.
