# Nadaraya Watson Envelop Alert

This is a custom indicator that calculates the Nadaraya Watson Envelop Alert for technical analysis in trading. It is developed by Forex Robot Easy Team and can be found on their website, [forexroboteasy.com](https://forexroboteasy.com).

## Indicator Overview

The Nadaraya Watson Envelop Alert indicator uses the Nadaraya Watson non-parametric regression method to calculate a trend line. It then calculates upper and lower envelopes based on the standard deviation of the price from the trend line.

The indicator has the following features:

- Trend line calculation using Nadaraya Watson non-parametric regression.
- Calculation of upper and lower envelopes based on standard deviation.
- Alerts, emails, and notifications when the price crosses above or below the envelopes.

## Indicator Parameters

The indicator has the following input parameters:

- `period`: Number of bars used for the calculation of the trend line and envelopes. Default value is 10.
- `bandwidth`: Bandwidth parameter used in the kernel function. Default value is 0.5.

## Indicator Initialization

The indicator initializes by setting up the necessary buffers for the trend line, upper envelope, lower envelope, and price data. It also sets the indicator label.

## Indicator Calculation

The indicator calculates the trend line using the Nadaraya Watson non-parametric regression method. It then calculates the upper and lower envelopes based on the standard deviation of the price from the trend line.

After the calculation, the indicator generates alerts, emails, and notifications when the price crosses above or below the envelopes.

## Custom Kernel Function

The indicator uses a custom kernel function to calculate the weights for the Nadaraya Watson regression. The kernel function takes the index, previous calculation value, and bandwidth as input and returns the weight.

## Disclaimer

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/nadaraya-watson-mt5-indicator-unbiased-review-results/).
