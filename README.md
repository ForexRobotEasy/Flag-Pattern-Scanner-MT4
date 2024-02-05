# Flag Pattern Scanner MT4 ReadMe

**Program**: Flag Pattern Scanner MT4
**Developer's Site**: forexroboteasy.com
**Developer**: Forex Robot Easy Team

## Introduction
The Flag Pattern Scanner MT4 is an indicator for MetaTrader 4 platform that identifies flag patterns in the market. Flag patterns are a common technical analysis pattern that signifies a continuation of the previous trend. This indicator helps traders to identify potential flag patterns and make informed trading decisions.

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Indicator Input Parameters
- `lookbackPeriod`: Number of bars to look back for flag pattern identification.
- `minFlagHeight`: Minimum flag height as a percentage of the previous trend.
- `maxFlagHeight`: Maximum flag height as a percentage of the previous trend.

## Global Variables
- `flagHeight`: Stores the height of the flag pattern.
- `flagLow`: Stores the low value of the flag pattern.
- `flagHigh`: Stores the high value of the flag pattern.
- `fibLevel38`: Stores the Fibonacci retracement level at 38%.
- `fibLevel50`: Stores the Fibonacci retracement level at 50%.
- `fibLevel61`: Stores the Fibonacci retracement level at 61%.

## Indicator Initialization Function
The `OnInit()` function is called during the indicator initialization process. It sets the indicator buffers and labels.

## Indicator Calculation Function
The `OnCalculate()` function is called for each new bar on the chart. It calculates the flag pattern and Fibonacci retracement levels based on the specified criteria. The function loops through all bars from the current to the lookback period and checks if the flag height meets the specified criteria. If a flag pattern is identified, the function calculates the flag low, flag high, and Fibonacci retracement levels.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com/forex-robot-review/flag-pattern-scanner-mt4-review-enhance-your-trend-trading-strategy/](https://forexroboteasy.com/forex-robot-review/flag-pattern-scanner-mt4-review-enhance-your-trend-trading-strategy/).

**Note:** The link provided for detailed reviews and trading results is for informational purposes only. Forex Robot Easy is not the official developer of this product.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
