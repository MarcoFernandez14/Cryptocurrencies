# Cryptocurrencies  
#### Environment    
Code editor: Jupyter Notebook      
Language: Python      
Libraries: pandas, scikit-learn, hvPlot, Plotly  

## Overview  
The purspose of the analysis is to advise Accountability Accounting, a prominent investment bank, about cryptocurrency investment. The analysis is focus on cryptocurrencies that are on the trading market and how they could be grouped to create a classification system.   
Since there is no known output for the analysis, it is a good case to use unsupervised learning.  

## Results   
After preprocessing the raw data, we use clustering algorithm and visualizations to share the findings.  

#### Clustering Crytocurrencies Using K-Means    
The K-means Elbow Curve indicates we should group the data in 4 custers.    
![Elbow Curve](https://github.com/MarcoFernandez14/Cryptocurrencies/blob/main/Resources/Elbow%20Curve.png)      
  
#### Visualizing Cryptocurrencies Results. 3D-Scatter.  
![3D Scatter](https://github.com/MarcoFernandez14/Cryptocurrencies/blob/main/Resources/3D%20Scatter.png)    

#### Visualizing Cryptocurrencies Results. Tradable Cryptocurrencies.  
![Tradetable](https://github.com/MarcoFernandez14/Cryptocurrencies/blob/main/Resources/Tradetable.png)    

#### Visualizing Cryptocurrencies Results. hvplot.scatter using x="TotalCoinsMined" and y="TotalCoinSupply".  
![2D Scatter](https://github.com/MarcoFernandez14/Cryptocurrencies/blob/main/Resources/2D%20Scatter.png)    
