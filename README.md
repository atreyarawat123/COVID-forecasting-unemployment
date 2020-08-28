# COVID-forecasting-unemployment

Atreya Rawat and Samir Singh

In an attempt to make predictions on the future of the economy, we explored multiple indicators from the Covid Tracking and Google Mobility data and aim to identify what would cause unemployment to be negatively impacted in the future.

For this project, we depended on several python libraries such as pandas, matplotlib.pylab, numpy, sklearn.linear_model, sklearn, sklearn.model_selection, and math.

## Data Prep

The 2020 COVID-19 pandemic has been a rapidly evolving infectious disease that has brought the entire world to a standstill. One of the keys to countries being able to mitigate the effects of the pandemic has been effective sharing of data to the public. There exist many channels for individuals to find aggregated data (for example, Johns Hopkins University, New York Times, local government websites, etc.) One of the more reputable and consistently updated data sets comes from the COVID Tracking Project at covidtracking.com. The COVID Tracking Project has a data set containing daily state-by-state information on COVID cases, deaths, and hospitalizations.

Google also has a data set called Google Mobility which keeps track of how many people are at specific places or participating in certain activities. The metrics are measured as a percent change from the baseline level of activity. There are metrics for retail and recreation, grocery stores and pharmacies, parks, public transit, workplaces, and residential areas.

One metric which highlights the severity of COVID-19's impact on the economy is unemployment rate. The BLS (Bureau of Labor Statistics) has a monthly aggregation of state-by-state unemployment rates publicly available at bls.gov. 
of data

These datasets can be found on the following sites: Google Mobility at https://www.google.com/covid19/mobility/, Covid Tracking at https://covidtracking.com/, unemployment at https://www.bls.gov/guide/geography/employment.htm, and New York Times Covid at https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html. To use these with the code from the github, these datasets need to be converted to .csv files.

## Models

CleanAnalysis.ipynb is a Jupyter notebook where the US population, Covid, and google mobility data are imported and several functions are created which show the correlation between date and covid cases and deths in the US. Also, the global mobility was converted to USA mobility.

Google Mobility + Covid Regression for Unemployment Rate.ipynb is also a Jupyter notebook where the US population, Google Mobility, bls unemployment, and covidtracking data are imported and linear regression, logistic regression, lasso regression, and ridge regression are use to determine the correlation between unemployment and covid cases and deaths with mobility in the US.  

## References

`https://www.google.com/covid19/mobility/`

`https://covidtracking.com/`

`https://www.bls.gov/guide/geography/employment.htm`

`https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html`



