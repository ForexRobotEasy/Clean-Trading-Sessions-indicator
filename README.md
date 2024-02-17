# Clean Trading Sessions Indicator

This is the source code for the Clean Trading Sessions indicator, developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 website.

## Description

The Clean Trading Sessions indicator is designed to highlight the trading sessions in the Forex market. It identifies three major trading sessions: London, New York, and Tokyo. During these sessions, the indicator plots the high, low, and close prices on the chart.

The indicator uses three indicator buffers: UpBuffer[], DownBuffer[], and NeutralBuffer[]. These buffers store the high, low, and close prices respectively for each bar.

The indicator also defines global variables to store the opening and closing times for each trading session.

## How It Works

The indicator is initialized in the OnInit() function, where the indicator buffers are set and the indicator labels are defined. The trading session times are calculated using the CalculateTradingSessions() function.

In the OnCalculate() function, the indicator iterates through each bar and checks if the current time is within a trading session. If it is, the high, low, and close prices are stored in the corresponding indicator buffers. If not, the buffers are set to 0.

The IsLondonTradingSession(), IsNewYorkTradingSession(), and IsTokyoTradingSession() functions are used to check if the current time is within the respective trading sessions.

## Product Description

The Clean Trading Sessions indicator is a powerful tool for optimizing trading strategies based on specific trading sessions. By visually displaying the high, low, and close prices during different sessions, traders can gain valuable insights into market behavior and make more informed trading decisions.

Key Features:
- Identifies three major trading sessions: London, New York, and Tokyo
- Plots the high, low, and close prices for each session
- Helps optimize trading strategies based on specific sessions
- Easy to use and customizable

For more detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/clean-trading-sessions-indicator-review-optimize-forex-market-sessions/).

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing the sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 website.
