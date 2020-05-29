# Avocado_Price_Predictions_Fbprophet
In this analysis, **Facebook prophet** time-series-analysis tool is used to predict future prices of avocado in the US.

The data is taken from [Kaggle.](https://www.kaggle.com/neuromusic/avocado-prices)
The dataset contains 14 columns. Description for some of them are as follows - 
- **Date**: The date of the observation
- **AveragePrice**: the average price of a single avocado
- **type**: conventional or organic
- **year**: the year
- **Region**: the city or region of the observation
- **Total Volume**: Total number of avocados sold
- **4046**: Total number of avocados with PLU 4046 sold
- **4225**: Total number of avocados with PLU 4225 sold
- **4770**: Total number of avocados with PLU 4770 sold

The dataset is described usnig various summary statistics and comprehensive visualizations (Line Plots, Bar charts, Violin Plots, Catplots etc.)

The data is then passed to the Facebook Prophet time-series-analysis tool is used to predict future prices of avocado in the US overall and in a specific region (West).

The predictions for the next year in the future are plotted in the end.

The complete analysis is done on [Google Colab](https://colab.research.google.com/), which makes it easier to use Fbprophet as no installation steps are needed.
