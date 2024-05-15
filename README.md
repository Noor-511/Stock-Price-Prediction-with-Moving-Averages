# Stock-Price-Prediction-with-Moving-Averages
This project investigates the potential of using moving averages (MA) as a trading signal for stock price prediction. We focus on Microsoft's historical data from 2015 to 2018 to evaluate a simple strategy based on comparing 10-day (fast) and 50-day (slow) moving averages.
The project covers the following key aspects:

Data Acquisition and Preprocessing: Utilize Python libraries like pandas to read and manipulate historical stock data (open, close, high, low, adjusted close).
Feature Engineering: Calculate 10-day and 50-day moving averages as new features for analysis.
Trading Strategy Development: Implement a basic strategy where a long position (buy or hold) is taken if the 10-day MA exceeds the 50-day MA, indicating a potential uptrend.
Strategy Evaluation: Analyze the performance of the strategy, considering factors like potential entry and exit points, and identify areas for improvement.
Limitations and Considerations: Discuss the inherent limitations of the moving average strategy, including potential for false signals and the influence of other market factors.
