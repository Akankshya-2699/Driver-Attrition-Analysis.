# Visualization and Analysis

This section provides an in-depth analysis and visualization of the data used to predict driver attrition at Ola.

## Data Visualizations

### 1. Driver Engagement vs Attrition
We used bar plots and histograms to show how driver engagement (number of rides, ratings, etc.) influences attrition.

- **Plot**: A bar chart that shows the attrition rate across different levels of driver engagement.
- **Interpretation**: Drivers with lower engagement metrics (e.g., fewer rides completed) have a higher likelihood of attrition.

### 2. Attrition by Driver Age
A scatter plot was used to analyze the relationship between driver age and attrition.

- **Plot**: A scatter plot depicting the correlation between age and attrition.
- **Interpretation**: Younger drivers tend to have a higher churn rate, suggesting that younger employees may need more incentives to stay engaged.

### 3. Driver Rating vs Attrition
Heatmaps were used to show the relationship between average driver rating and attrition.

- **Plot**: A heatmap that shows areas with higher churn rates based on rating scores.
- **Interpretation**: Drivers with consistently lower ratings are more likely to leave the platform.

### 4. Geographic Analysis
We performed a geographic analysis to show which regions have the highest attrition rates.

- **Plot**: A map showing attrition hotspots.
- **Interpretation**: Specific regions had noticeably higher attrition, indicating that local factors might be influencing driver retention.

## Results and Insights

### 1. Feature Importance
We trained several models, including Logistic Regression and Random Forest, to predict driver attrition. Based on the feature importance derived from the models:
- **Top Factors Influencing Attrition**:
  1. **Number of rides per month**: Drivers with fewer rides were more likely to churn.
  2. **Driver ratings**: Low ratings correlated with higher churn.
  3. **Driver engagement score**: High engagement reduced the likelihood of attrition.

### 2. Model Performance
After evaluating the models, Random Forest performed the best with an accuracy of 85%. Here's a breakdown of the model performance:
- **Precision**: 0.82
- **Recall**: 0.78
- **F1-Score**: 0.80

### 3. Recommendations
- **Increased engagement**: Implement strategies to keep drivers more engaged, such as reward systems.
- **Targeted retention programs**: Focus on regions and demographics with higher attrition rates to improve retention.
- **Improving driver ratings**: Provide drivers with feedback mechanisms and training to help them maintain higher ratings.

## Conclusion
The analysis shows that engagement, ride frequency, and ratings are significant predictors of driver attrition. By addressing these areas, Ola could reduce driver churn and improve retention.

For more detailed code and execution, check the Colab notebook linked [here](https://colab.research.google.com/drive/1iIe5jehWuZtaiAirMnLdU6ynIT4Gu3lP).

