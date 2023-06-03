# *challenge-10-052523*
---
**Repository for challenge 10 for FinTech BootCamp**
---
## Cyrpto Investing

![Image used from original FinTech challenge files](/Starter_Code/Images/10-5-challenge-image.png)
The purpose of this challenge was to analyze cyrptocurrencies by analyzing other features other than returns and volatility using machine learning. By analyzing other characteristics of the currency, we can identify patterns and build a portfolio around these patterns. 

## Technologies

This project leverages python 3.7 specifically and assumes that jupyter lab has been installed. In additon, you would need to have the following modules installed:
* pandas
* hvplot
* sklearn
* voila

## Resources
* Data provided by Columbia FinTech program.

## Contributions 

Historical data and challenge questions provided by Columbia FinTech progam.
Analysis, code, and conclusions completed by Sean Senhouse

## Installation Guide
### To review challenge 10:

* The jupyter notebook can be viewed using as a web application using viola. In order to use voila you need to first install voila. Install voila in the command prompt by first typing:

```python
pip install viola
```
* Once viola is installed you can navigate to where the notebook is saved on your machine. In the command prompt you can run the notebook by typing in the following:

```python
voila <filename path> 
```

* Alternatively the notebook can be viewed in a jupyter web application

## Usage
The code imports the data from csv files. The code then generates the following charts: 

Figure 1 shows the elbow plot using kmeans. The elbow plots are of the orignal data as well as using and comparing to using Principal Component Analysis (PCA). 
![elbow_plots](/Starter_Code/images/elbow_plots.png)

Figure 2 shows the scatter plots. This shows the comparison of two features of the crypto currencies using the original data. Then compare it using Principal Component Analysis. 
![scatter_plots](/Starter_Code/images/scatter_plots.png)

## Final Recommendations
Comparing the results between the elbow data, choosing k = 4 fits both the original and the PCA analysis. However, comparing the scatter plots shows that reducing the number of features could create clusters with "closer" alignment. Both scatter plots illustrate that "ethelend" is more of an extreme crypto and, therefore, not one we may include in our cluster. However, reducing the features can make us more confident in creating two separate clusters for our portfolio analysis.