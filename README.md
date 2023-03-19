# Smoothing-for-Data-Science

Developing of three diferent methods for smoothing data in Python.


* Savitzky-Golay Filter

  * A smoothing technique used to reduce noise in data while preserving the shape of the underlying signal. It works by fitting a polynomial function to a small window of data points and using that polynomial to estimate the value of the central point in the window. This process is repeated for each point in the data, resulting in a smoothed curve.

* Moving Average Filter

  * Works by replacing each data point with the average value of its neighboring points within a window of a fixed size. The basic idea is to slide the window over the data, taking the average of the data points within the window at each position. This results in a new sequence of smoothed values that can be used to analyze the signal with reduced noise. 

* Exponential Filter

  * Reduces noise in a signal by applying a weighted average of past and current data points. The weights assigned to each data point decrease exponentially as the data gets older, with more recent data points having greater influence on the smoothed output.
