# RSI Divergence Full

This code is a custom indicator for MetaTrader 5 (mql5) that detects and identifies divergences between price movements and the RSI indicator. It provides functions to detect both bullish and bearish divergences.

## Indicator Inputs

The indicator has one input parameter:

- RSI_Period: The period for the RSI indicator. Default value is 14.

## Expert Advisor Functions

The code consists of several functions that handle different aspects of the expert advisor's logic:

1. OnInit(): This function is called during the expert advisor's initialization. Any necessary initialization code can be placed here.

2. OnTick(): This function is called on every tick. The main trading logic of the expert advisor should be implemented here. In this code, three example functions are called: `DetectDivergence()`, `IdentifyBullishDivergence()`, and `IdentifyBearishDivergence()`.

3. DetectDivergence(): This function contains the code to detect divergences between price movements and the RSI indicator.

4. IdentifyBullishDivergence(): This function contains the code to identify bullish divergences.

5. IdentifyBearishDivergence(): This function contains the code to identify bearish divergences.

6. OnDeinit(): This function is called during the expert advisor's deinitialization. Any necessary cleanup code can be placed here.

## Product Description

This code serves as a sample implementation of the RSI Divergence Full indicator. It can be used to detect and identify divergences between price movements and the RSI indicator in MetaTrader 5. The RSI Divergence Full indicator is a powerful tool for identifying potential trend reversals and entry/exit points in the Forex market.

Please note that ForexRobotEasy is not the official developer of this product. We provide this sample code to demonstrate how the indicator works. For detailed reviews and trading results of the official product, please visit [this link](https://forexroboteasy.com/forex-robot-review/rsi-divergence-full-review-forex-software-with-5-other-divergence-indicators/). To find the official developer of this product and obtain the official version, please use MQL5.
