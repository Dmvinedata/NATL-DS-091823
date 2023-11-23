# Time Series: Modeling

Main goal here is to demonstrate time-series modeling and ultimately showing an example modeling task.

## Learning Goals

- Build simple models like the white noise and random walk models
- Explain auto-regressive and moving-average models

## Lecture Materials

[Jupyter Notebook: Time Series Modeling](time_series_modeling.ipynb)

## Lesson Plan

Provide a breakdown of the lecture activities using the structure below. 

### Introduction (5 Mins)

- Discuss now we know how to get a time series into a stationary time series, we can focus on modeling.

### White Noise Model (5 Mins)

- Discuss and demonstrate one of the simplest models that does not depend on prior data points.
- Show how it can be produced.
- Explain how it can be the building block for more complex models.

### Random Walk (5 Mins)

- Point out how it uses the white noise model but now has some temporal dependence.
- Demonstrate the variation of the model, random walk with a drift.

### Auto-Regression and Moving-Average Models (10 Mins)

- Demonstrate and explain how the AR model is created with the random walk and white noise models.
- Make comparisons with MA model and the AR model but how the MA model uses previous error. 
- Discuss and show how the parameters affect how the model behaves.

### ARMA Model (5 Mins)

- Conclude model types with how the AR and MA models can be combined and be dependent on different data points in time.

### Forecasting (10 Mins)

- Discuss how one would go about modeling time series with fixed paritioning and rolling-forward paritioning.
- Introduce a typical baseline model, naive forecast (look-ahead by one)
- Emphasize what time series modeling looks like when put into production and how it differs from previous ML model validation and evaluation.

### Demostrate Modeling (15 Mins)

- Use the Chicago gun data to demonstrate how to build up an ARMA model.
- If time permits and/or interests peaks, there is more infor in the Level Up section.

### Conclusion (5 Mins)

- Summarize there's so much more! But this is a good amount to abosorb!
