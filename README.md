# ASPCT Boom Crash Overloader

This code is a custom indicator developed by the Forex Robot Easy Team. It is designed to calculate spike directions for various index symbols and display them on the chart. The indicator can be used to identify potential market spikes and determine the direction of these spikes for different index symbols.

## Index Symbols

The following index symbols are defined in the code:

- Boom300: Boom 300 Index
- Boom500: Boom 500 Index
- Boom1000: Boom 1000 Index
- Crash300: Crash 300 Index
- Crash500: Crash 500 Index
- Crash1000: Crash 1000 Index

## Line Colors

The code defines three line colors:

- gray: Gray color
- green: Green color
- red: Red color

## Custom Indicator Initialization

The `OnInit()` function is called during the initialization of the custom indicator. It sets up the indicator labels by creating horizontal lines on the chart and sets their colors to gray.

## Custom Indicator Calculation

The `OnCalculate()` function is called for each bar on the chart to calculate the spike direction for each index symbol. It calls the `CalculateSpikeDirection()` function for each index symbol and sets the line colors based on the spike direction. It also checks if trades should be opened in the opposite direction of the spikes and updates the line colors accordingly.

## Spike Direction Calculation

The `CalculateSpikeDirection()` function is responsible for calculating the spike direction for a specific index symbol. This function performs calculations and determines the spike direction based on the close prices of the bars.

## Check Open Trades Opposite

The `CheckOpenTradesOpposite()` function checks if trades should be opened in the opposite direction of the spikes. It takes into account the trader's risk tolerance and returns true or false.

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/aspct-boom-crash-overloader-review-spike-targeting-forex-indicator/). To find the official developer of this product, please use MQL5.
