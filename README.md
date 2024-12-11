# Stock Price Analysis Using Plotly

This project leverages **Plotly** for interactive data visualization to analyze the stock performance of five major companies from the NSE website: **SBI**, **HDFC**, **ICICI**, **AXIS**, and **KOTAK**.

## Data Cleaning
The raw stock data was cleaned and preprocessed using **Pandas** to ensure accuracy and consistency. Key steps included:
- **Data Type Conversion**: The `Date` column was converted to `datetime` format for easy time-based operations.
- **Feature Extraction**: Extracted additional features such as `Year`, `Month`, `Day`, and `Day_of_week` from the `Date` column to enable detailed analysis.
- **Additional Column**: New column 'stock_name' is included to identify each DataFrame's stock
- **Data Reshaping**: Reorganized and transformed data using `melt` and `groupby` operations for specific visualizations.

## Data Visualization
Dynamic and interactive visualizations were created using **Plotly** to uncover patterns and trends in stock performance.

### Key Insights:

#### Insight 1: Closing Prices Over the Years
An animated bar plot highlights how the closing prices of the selected stocks have evolved year by year, providing a clear comparative view of their performance.

#### Insight 2: Daily Closing Prices
An animated visualization showcases daily variations in closing prices, helping to observe short-term movements and trends for each stock.

#### Insight 3: Average Closing Price by Day of the Week
Bar charts reveal the average closing prices for each day of the week, uncovering weekday-specific patterns in stock performance.

#### Insight 4: Average Trading Volume by Stock Over Years
An animated bar chart displays the average trading volume for each stock over the years, providing insights into trading activity trends.

#### Insight 5: High vs. Low Price Distribution
A box plot compares the distribution of high and low prices for each stock, emphasizing the range and variability in their performance.

#### Insight 6: Weekly Trends Over the Years (Line Chart)
A line chart visualizes trends in average weekly closing prices for each day of the week across multiple years, highlighting consistent patterns and anomalies.

#### Insight 7: Weekly Trends Over the Years (Grouped Bar Chart)
A grouped bar chart compares the average closing prices for weekdays across multiple years, providing year-wise variations for specific weekdays.

## Technologies Used

- **Python**: Core programming language for data analysis and visualization.
- **Pandas**: For efficient data preprocessing and cleaning.
- **Plotly**: For creating interactive, animated, and professional-grade visualizations.

## Future Scope

1. Expanding the dataset to include a wider range of stocks from various sectors for a more comprehensive analysis.
2. Exploring and understanding 3D visualizations in Plotly to represent multidimensional data such as price, volume, and time simultaneously for enhanced insights.

## Conclusion
This project demonstrates the power of **Plotly** in creating dynamic and insightful visualizations for stock market analysis. It offers a clear understanding of stock performance trends, helping users make informed decisions.
