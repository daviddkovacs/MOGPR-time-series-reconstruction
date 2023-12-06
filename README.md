# MOGPR-time-series-reconstruction
Time series reconstruction and gap-filling by satellite sensor fusion

Welcome!

You can find the code here for using Multi-Output Gaussian Process (MOGPR) regression that fuses different satellite time series to either do gap-filling or past data reconstruction.

It is primarily based on retrieving time series from Google Earth Engine. The example is given by reconstructing Sentinel-3 based vegetation products (as described in https://www.mdpi.com/2072-4292/15/13/3404). Then we use MODIS time series to reconstruct Sentinel-3 back to 2002, or your preferred timeframe.
If you want to use this algorithm for sensor fusion, i.e. gap-filling, you can do so. Suppose you feed the MOGPR algorithm with 1 year of Sentinel-3 data, and the same year of MODIS data, it will essentially "fuse" the time series, to create a new smooth, fused, gap-free one.

Please do not hesitate to contact me if you have any questions.
koda@uv.es
