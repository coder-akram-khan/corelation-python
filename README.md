# Understanding Correlation in Python
![cover](https://github.com/coder-akram-khan/corelation-python/blob/main/Pairplot.png?raw=true)
This repository demonstrates various aspects of correlation analysis using Python. It covers the fundamentals of covariance, correlation types, and visualization techniques to explore relationships between variables across different datasets.

## Observations from the Plots

### Pairplot for Penguins Dataset

- **Strong Correlation:** There seems to be a strong positive correlation between `flipper_length_mm` and `body_mass_g`.
- **Distinctive Clusters:** The three species (Adelie, Chinstrap, Gentoo) appear to form distinct clusters based on their measurements.
- **Possible Outliers:** There are a few data points that seem to deviate from the overall trends within each species cluster.

### Pairplot for Numerical Features (Iris Dataset)

- **High Correlation:** `petal_length` and `petal_width` are highly correlated, suggesting they might be describing similar features.
- **Moderate Correlation:** `sepal_length` and `petal_length` show a moderate positive correlation.
- **No Clear Correlation:** `sepal_width` appears to have less correlation with other features.

### Heatmap: Pearson Correlation (Iris Dataset)

- **Strong Positive Correlation:** Confirms the high positive correlation observed in the pairplot between `petal_length` and `petal_width`.
- **Moderate Positive Correlation:** Confirms the moderate correlation between `sepal_length` and `petal_length`.
- **Weak Correlation:** The correlation between `sepal_width` and other features is quite weak, as seen in the pairplot.

### Regression Plot: 'pclass' vs 'fare'

- **Negative Trend:** There is a negative trend between the passenger class (pclass) and the fare, meaning higher passenger classes tend to have lower fares.

### Heatmap: Pearson Correlation (Titanic Dataset)

- **Weak to Moderate Correlation:** Overall, the correlations among features in the Titanic dataset seem weak to moderate.
- **Negative Correlation:** `pclass` has a negative correlation with `fare`, indicating higher passenger classes tend to have lower fares (consistent with the regression plot).
- **No Strong Correlation:** There's no strong correlation between `survived` and any other feature, suggesting that survival is not easily predicted based on these variables alone.

## How to Use This Repository

1. **Clone the Repository**
   ```bash
   git clone https://github.com/coder-akram-khan/corelation-python.git
   cd corelation-python
   ```

2. **Install Dependencies**
   Make sure you have Python and the required libraries installed. Use the `requirements.txt` file to install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**
   Open the `CoRelation.ipynb` file in Jupyter Notebook or any compatible editor to explore the analyses and visualizations.
