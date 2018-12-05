# Statistics and Plots


Statistical Analysis of heavily imbalanced datasets might be slightly different than a balanced data set.

# Plots

## 2D scatter plots

Adding plots of iris dataset as example
``` python
iris.plot(kind='scatter', x='sepal_length', y='sepal_width')
```
<img src="https://github.com/srvds/ML-Brushup/blob/master/Day-1/Photos/2D-scatter-Plot.png">

Color the points by thier class-label
``` python
sns.FacetGrid(iris, hue="species", size=4).map(plt.scatter, "sepal_length", "sepal_width").add_legend()
```
<img src="https://github.com/srvds/ML-Brushup/blob/master/Day-1/Photos/2D-scatter-Plot-color.png">
 
## 3D scatter plots
 
https://plot.ly/pandas/3d-scatter-plots/
 
## Pair Plot
 
The diagnol elements are PDFs for each feature.
<img src="https://github.com/srvds/ML-Brushup/blob/master/Day-1/Photos/pair-plot.png">
 
## Probability Density Graph

Smoothening out histogram gives the PDF
