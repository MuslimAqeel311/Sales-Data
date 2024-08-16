# Sales-Data
This project involves a detailed analysis of a liquor sales dataset. The Project focuses on exploring and visualizing various aspects of the sales data to uncover patterns and trends that could inform business decisions
## 1. Data Loading
The dataset is loaded into a pandas DataFrame, which includes sales records with various attributes like 'State Bottle Cost,' 'Bottles Sold,' 'Sale (Dollars),' and 'Volume Sold (Liters).'
## 2. Exploratory Data Analysis (EDA)
### Distribution of Numerical Variables

Histograms and box plots are used to visualize the distribution of numerical variables, revealing key insights such as the spread and central tendencies of sales data.
The histogram plots for variables like 'Sale (Dollars)' and 'Bottles Sold' show the distribution of sales across different ranges.
Box plots help identify outliers in the data, providing a visual representation of the variance and potential anomalies.
### Correlation Matrix

A correlation matrix is generated to understand the relationships between different numerical variables. For instance, how 'State Bottle Cost' correlates with 'Sale (Dollars)' can help identify pricing strategies that maximize sales.
## 3. Categorical Analysis
### Top Categories by Frequency

Bar charts display the top 20 most frequent categories for attributes like 'Store Name,' 'City,' 'Product,' 'Vendor,' and 'County.'
These visualizations highlight the most active stores, popular cities for liquor sales, and leading products and vendors, which can guide marketing and inventory decisions.
### Monthly Sales Trend

A time series plot of monthly sales data reveals trends over time, such as seasonal spikes or declines, helping in forecasting future sales and planning inventory.
## 4. Key Insights
The analysis identifies top-performing stores and cities, key products driving sales, and vendors contributing the most to revenue. These insights are critical for targeting high-revenue areas and optimizing product availability.
Correlations between different variables, such as 'Bottles Sold' and 'Sale (Dollars),' provide a deeper understanding of what drives sales, allowing for better pricing and promotional strategies.
The time series analysis of sales data can be used to predict future sales trends, aiding in more accurate demand forecasting and inventory management.
# Predictive Modeling 
The predictive modeling process involved training a deep neural network using the Sequential API in Keras. The model architecture included several dense layers with ReLU activation, dropout for regularization, and batch normalization to stabilize the training process. The model was evaluated on test data, achieving a Mean Absolute Error (MAE) of approximately 23.59 and an R-squared (R²) value of 0.92, indicating strong predictive performance.
