# Visualization

Presentation of data in graphical or visual form to understand the data rather easily.  

## Various Graphs and Charts  

### Univariate Analysis

Used to understand the distribution, range, and frequency of a single feature.

#### Histogram

Histogram groups continous data into bins and shows how many data points fall into each bin. It reveals the shape of the distribution. The X-axis represents the value of the variable being measured divided into intervals called bins. The Y-axis could be the frquency.  
The graph reveals the shape of the distribution. For instance - bell shape (concentrated around the center).

#### Density Plot (KDE)

Instead of bars, it uses a continous curve. Hisogram changes shape depending on how many bins we choose. KDE provides a smoother view. Effective, when we want to overlay multiple distributions on top of each other to compare.

#### Count Plot

While histogram is for numbers, count plot is for categorical data. Count plots are for categorical data. 

#### Pie Chart

Serves a similar purpose as the bar chart. More inclined towards showing the part to whole relationship. However, scientists seem to prefer bar charts more as human eye is better in detecting the difference between two heights than two angles.

### Bivariate Analysis

Used to find correlation between two specific features. Now it can be one of the three given cases:

#### Numerical vs Numerical

1. Scatter Plot: Gold standard. Shows the direction and strength of the relationship. 
2. Line Plot: Best for trends over time. 


#### Categorical vs Categorical

1. Heatmap: Shows the concentration of two categories.
2. Stacked Bar Chart.

#### Numerical vs Categorical

1. Grouped Box Plot
2. Violin Plot

### Multivariate Analysis

#### Heatmap

A Color-coded grid that shows the correlation coffecient between every pair of features. Darker colors represent a stronger relationship.

#### Pair-Plot matrix (Scatterplot matrix)

A pair plot creates a scatter plot for each possible pair of features. The diagonal usually shows a histogram or KDE for the univariate view.   
One often adds a hue to the dots based on the categorical variable to see how groups differ across all features.

#### Bubble Chart 

A bubble chart is an advanced scatter plot where the size and color of the dots represent the 3rd and 4th variables. It allows us to visualize 4 dimensions of data:  
variable 1 -> X-axis     
variable 2 -> Y-axis   
variable 3 -> bubble size   
variable 4 -> bubble color  

etc.