# Click Through Rate (CTR) - outlier detection

This repo. contains the code for summarizing and visualizing impression data 
and two methods of detecting outliers in the calculated CTR time-series.
1.  I have grouped the impressions by hour and calculated the click through rate and visualized it as a time series.
2.  I have used two methods to recognize outliers and have annotated and plotted them. The first method is a standard moving average method which utilizes a the moving average function at it's core as requested.The second method which I did for comparison is a LOESS based method which accounts for trend and seasonality as well.

### Running the code
Place the train.gz file in the working directory

#### Dependencies

* Code ran on a Windows 10 Pro x64 machine with 16GB RAM
* jupyter notebook
* python 3.8.8
* pandas version 1.2.4
* numpy version 1.20.1
* seaborn version 0.11.1
* matplotlib version 3.3.4

## Author
Nissanka Wickremasinghe
## Acknowledgments

Inspiration
* [A review on outlier/anomaly detection in time series data](https://arxiv.org/abs/2002.04236)
* [Anomaly Detection- Key Feature - article](https://towardsdatascience.com/anomaly-detection-def662294a4e)
* Numerous other sources

