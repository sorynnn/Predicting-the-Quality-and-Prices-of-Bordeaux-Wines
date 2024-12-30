# Predicting-the-Quality-and-Prices-of-Bordeaux-Wines

**Author**: Orley Ashenfelter (Princeton University)  
**Source**: No 37297, Working Papers from the American Association of Wine Economists  

### Project Overview  
This project draws inspiration from the work of economist Orley Ashenfelter, who combined his love for wine with his econometric expertise to develop a method for predicting the quality and prices of Bordeaux wines. Frustrated by the high costs of premium wine and the subjective nature of expert opinions, Ashenfelter demonstrated that the quality and market value of Bordeaux vintages can be reliably predicted using weather data from the grape-growing season.  

The wine dataset, adapted from Ashenfelter's original study, includes data on 27 red Bordeaux vintages with variables such as vintage year, climate characteristics, and wine price. The analysis provides insights into market inefficiencies, the impact of climate change on wine production, and the marginal effect of weather on wine prices.  

### Analysis Highlights  
Within the R Markdown file:  
- **Regression Models**: Multiple regression techniques were used, including quadratic terms to capture nonlinear relationships.  
- **Model Comparison**: F-tests were conducted to compare the explanatory power of different models.  
- **Heteroscedasticity Correction**: Standard errors were adjusted to account for heteroscedasticity in the data.  
- **Marginal Effects**: Calculated using the `margins` package to interpret the influence of key predictors.  

### Key Insights  
- Weather data plays a significant role in predicting the quality and prices of Bordeaux vintages.  
- The price equation suggests a real rate of return for holding wines of about 2–3% per annum, uncovering market dynamics.  
- The analysis highlights potential inefficiencies in the wine market and provides a foundation for studying climate change's impact on the wine industry.  

This repository showcases an econometric approach to understanding wine markets, offering tools and methods for anyone interested in wine economics, predictive modeling, and data-driven insights.  
