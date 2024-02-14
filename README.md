## Validate SARIMAX on a given test/validation set by different strategies.

Validate SARIMAX on a given test/validation set on different strategies:
1. Insample prediction
2. Out of sample forecasting with recursion
3. Out of sample forecasting considering new observation into account withot refitting SARIMAX on newly observed data
4. Out of sample forecasting considering new observation into account with refitting SARIMAX on newly observed data
# Run
* Install the required libraries such as pandas, numpy, pmdarima, statsmodels, matplotlib, prettytable (if not already installed) by **pip install library_name**
* Run the file **SARIMAX_VALIDATION_Insample_OutOfSample_WithAndWithout_REFIT.ipynb**
<br />
<img width="499" alt="validation_plot" src="https://github.com/ahmadaliabin/SARIMAX_VALIDATION_Insample_OutOfSample_WithAndWithout_REFIT/assets/34601110/33df7b70-ea22-429b-8d65-c9efce1bd102">
<br />
<img width="353" alt="residual_kde_plot" src="https://github.com/ahmadaliabin/SARIMAX_VALIDATION_Insample_OutOfSample_WithAndWithout_REFIT/assets/34601110/baaecb9c-918f-49fd-8ba7-a038f067aa7d">
<br />
<img width="475" alt="error_plot" src="https://github.com/ahmadaliabin/SARIMAX_VALIDATION_Insample_OutOfSample_WithAndWithout_REFIT/assets/34601110/d274ce29-4a40-4384-84d8-b634bacfffd1">
