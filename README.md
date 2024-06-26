# Multi-Timeframe Moving Average Levels

You can find this indicator on Tradingview at https://www.tradingview.com/script/lCRNeqoQ-Multi-Timeframe-MA-Levels/

## OVERVIEW

This Pine Script is an indicator for displaying multiple moving average (MA) levels from several timeframes on your TradingView charts.  At the Realtime Bar (the right-most bar on your chart), it draws a line where the various moving averages currently are.

For example, it will show you where the 8 EMA on the 5-minute timeframe is on your 1-minute timeframe chart.

It derives its look and function from "Lepelle's Key Levels" and focuses on visualizing various moving averages to complement this indicator.


## FEATURES

1. Multi-Timeframe Analysis:
   * The script allows traders to view moving averages from different timeframes on a single chart. This multi-timeframe approach helps identify significant levels and trends that might not be apparent when looking at a single timeframe.

2. Customization and Flexibility:
   * Extensive input options for customizing the appearance of the lines (width, style, color) and labels (size, position, distance from price). This ensures that the indicator can be tailored to individual preferences and charting styles.

3. Multiple Moving Averages:
   * Support for various types of moving averages (8 EMA, 21 EMA, 50 SMA, 100 SMA, 200 SMA). Each moving average can be individually enabled or disabled for specific timeframes, providing a flexible tool for technical analysis.


## SETTINGS

### Inputs for Styling:

* Controls the appearance of the lines and labels.
* Includes options for line width, line style, text size, distance from the candlesticks, label position, and whether to hide prices or use shorthand notation.

### Moving Averages Settings:

* Inputs to select different moving averages (8 EMA, 21 EMA, 50 SMA, 100 SMA, 200 SMA) and their corresponding colors.
* Boolean inputs to enable or disable these moving averages on various timeframes (2 min, 5 min, hourly, daily).


## SUMMARY

In essence, this script provides a comprehensive tool for technical analysis by combining multi-timeframe moving averages into a single, customizable, and user-friendly indicator. It enhances traders' ability to make informed decisions by providing clear visual representations of key moving average levels across different timeframes.


═════════════════════════════════════════════════════════════


## LIMITATIONS

This script is best used with a short timeframe such as 1-minute or lower because of the limitations of Multi-Timeframe scripts.  Basically, the alternate timeframes in use should always be higher than the chart timeframe.


═════════════════════════════════════════════════════════════


## NOTES


This indicator is intended to complement and be used with [url=https://www.tradingview.com/script/ltF1SePF-Lepelle-s-Key-Levels/]"Lepelle's Key Levels"[/url] indicator.

In that indicator settings, I recommend turning off the 5 Daily timeframe moving average levels in that script, if using this one.


═════════════════════════════════════════════════════════════
