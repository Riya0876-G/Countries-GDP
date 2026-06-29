# Countries-GDP
Analyzing GDP Growth Using Machine Learning

Can one country's GDP growth predict another's? This project applies ML regression models on World Bank data (top 10 & bottom 10 economies) to explore cross-country economic interdependencies.

Four models were tested — Linear Regression, Ridge Regression, Random Forest, and KNN. Random Forest performed best (R² = 0.084), confirming that cross-country GDP relationships are nonlinear and complex, not captured well by simple linear approaches. KNN showed weak performance (R² = -0.42), while Linear Regression offered a moderate baseline.

The analysis reveals that GDP growth is shaped by multiple countries simultaneously — making ensemble methods more suitable for this kind of global economic forecasting.

Tools: Python · pandas · scikit-learn · matplotlib · Google Colab

Data: World Bank | Course: Machine Learning, Christ University Bangalore
