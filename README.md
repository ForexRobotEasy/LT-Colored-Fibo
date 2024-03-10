## LT Colored Fibo

![LT Colored Fibo](https://forexroboteasy.com/wp-content/uploads/2022/01/lt-colored-fibo-indicator.jpg)

This is a code sample for the LT Colored Fibo indicator developed by Forex Robot Easy Team. This indicator generates Fibonacci retracement zones on a chart and executes trading actions based on these zones.

### Features

- Calculates Fibonacci retracement levels based on the current price range.
- Defines price zones and their respective colors.
- Displays the price zones on the chart.
- Executes buy or sell trades based on the current price position within the zones.
- Closes any existing trades when the price enters the lowest zone.

### How it works

1. The code first includes the necessary Trade library for executing trades.

2. The colors for each Fibonacci retracement level are defined using the `color` data type.

3. The display options are defined using the `bool` data type. If `display_in_background` is set to `true`, the zones will be displayed in the background. Otherwise, they will be displayed in the foreground.

4. The `GenerateFiboZones` function is defined, which takes three Fibonacci retracement levels as parameters.

5. Inside the function, the current chart symbol and timeframe are obtained using the `Symbol` and `Period` functions.

6. The Fibonacci retracement levels are calculated based on the highest and lowest prices of the current candle.

7. The price zones and their respective colors are defined based on the display options.

8. The price zones are drawn on the chart using the `ObjectCreate` and `ObjectSet` functions.

9. Trading actions are executed based on the current price position within the zones. If the price is within the first zone, a buy trade is placed. If the price is within the second zone, a sell trade is placed. If the price is within the lowest zone, any existing trades are closed.

10. The `OnInit` function is called at the entry point of the program. It sets up the necessary chart parameters.

11. The `OnTick` function is called in a loop and calls the `GenerateFiboZones` function with the specified Fibonacci retracement levels.

12. The `OnDeinit` function is called at the program termination. It cleans up any remaining objects on the chart.

### Product Description

The LT Colored Fibo indicator is a powerful tool developed by Forex Robot Easy Team. It simplifies the process of identifying Fibonacci retracement zones and executing trades based on these zones.

With the LT Colored Fibo indicator, traders can easily visualize the Fibonacci retracement levels on their charts. The indicator automatically calculates the levels based on the current price range and displays them in different colors for easy identification.

Traders can choose to display the zones in either the background or foreground, depending on their preference. The indicator also provides the option to execute buy or sell trades based on the current price position within the zones. Additionally, any existing trades can be closed when the price enters the lowest zone.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a code sample that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/lt-colored-fibo-review-of-simplified-forex-indicator-tool/).
