# Volatility Scanner Multi TF

## Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)
## Developed by: Forex Robot Easy Team

This code is a volatility scanner that detects and colors buttons for potential trading opportunities. It scans all timeframes for volatility contraction and highlights them using the specified color.

## How it Works

The code sets up a user-friendly interface with a button that represents a trading opportunity. It defines the color of the button using the `yellowColor` variable.

In the `OnInit()` function, the button is created and styled with the specified color and text. This function is called when the script is initialized.

In the `OnTick()` function, the code loops through all timeframes, from M1 to D1. It calculates the range of market volatility for each timeframe using the `CalculateVolatilityRange()` function.

If the calculated volatility range is significantly lower than its normal range (threshold defined as 0.5), the corresponding button is colored yellow.

The `CalculateVolatilityRange()` function calculates the range of market volatility for a given timeframe. It retrieves the current high and low prices and subtracts them to get the range.

## Product Description

Volatility Scanner Multi TF is a powerful tool developed by the Forex Robot Easy Team. It accurately identifies potential trading opportunities by scanning multiple timeframes for volatility contraction.

With its user-friendly interface, this tool provides traders with a quick and efficient way to spot profitable trades. The colored buttons highlight the periods of low volatility, allowing traders to take advantage of potential breakouts or reversals.

Whether you are a beginner or an experienced trader, Volatility Scanner Multi TF can help you make informed trading decisions. Its intuitive design and reliable performance make it an essential tool for any trading strategy.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that demonstrates how this product works. For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/volatility-scanner-multi-tf-unveiling-profitable-trades-review/). To find the official developer of this product, we recommend using the MQL5 platform.
