# Wind Turbine Analysis Project

This project provides Python code to analyze wind turbine data and calculate various performance metrics. It can be used to assess the power generation potential of a wind farm site and compare the performance of different turbine models.

## Requirements

This project requires the following Python libraries:

- pandas
- numpy
- scipy (for the Weibull distribution function)
- matplotlib
- windrose (optional, for wind rose plots)

You can install these libraries using the pip command:

```bash
pip install pandas numpy scipy matplotlib windrose
```

## Steps to run
Simply run the notebook from the top, it assumes that you have the Ouessant.csv in the same directory (as it loads directly from it) if you intend to use your own data make sure the CSV is added to the same directory and adjust the line
```python
pd.read_csv('YOUR FILE NAME')
```

Make sure your csv at least has the columns documented here
```python
related_features = ['period_end', 'period', 'wind_speed_10m', 'wind_speed_100m', 'wind_direction_100m', 'wind_direction_10m']
```

