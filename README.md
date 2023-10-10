# 1BullBear-Pine-Codes

Curated PineScript® codes for 1BullBear® Trading Community

Here are file names and how to use it.

## (1) Unicorn.pine

This is all-in-one utility tool that provide visual helper to -

1. **Sessions**
We use different approach in session mapping to autodetect Day Light Saving.
    Each session time is their local time so that it make sense of setting the right time-based intraday strategy.

2. **Daily Session Divider**
Turn on separator according to Exchange trading timezone for all - Forex, Equity and Crypto.

3. **Fractals**
Added Fractals based on William Fractal rules to assist the immediate trend.

4. **Momentum Technical Rating**
Added technical rating based on 20+ technical indicators.

5. **Previous Day High / Low + New York Midnight Open**
Added lines to plot previous day High, Low and current day New York Midnight open price to understand algorithm agenda.

6. **Swing and Internal High / Low Liquidity**
This experimental feature help you identify buyside and sellside liquidity based on 14 look-back pivot value along with volume.

## (2) SMC.pine

This all-in-one indicator displays real-time market structure (internal & swing BOS / CHoCH), order blocks, premium & discount zones, equal highs & lows, and much more...allowing traders to automatically mark up their charts with widely used price action methodologies. Following the release of our Fair Value Gap script, we received numerous requests from our community to release more features in the same category.

"Smart Money Concepts" ( SMC ) is a fairly new yet widely used term amongst price action traders looking to more accurately navigate liquidity & find more optimal points of interest in the market. Trying to determine where institutional market participants have orders placed (buy or sell side liquidity) can be a very reasonable approach to finding more practical entries & exits based on price action.

The indicator includes alerts for the presence of swing structures and many other relevant conditions.

> Features

This indicator includes many features relevant to SMC , these are highlighted below:

* Full internal & swing market structure labeling in real-time
* Break of Structure (BOS)
* Change of Character (CHoCH)
* Order Blocks ( bullish & bearish )
* Equal Highs & Lows
* Fair Value Gap Detection
* Previous Highs & Lows
* Premium & Discount Zones as a range
* Options to style the indicator to more easily display these concepts

> Settings

* Mode: Allows the user to select Historical (default) or Present, which displays only recent data on the chart.
* Style: Allows the user to select different styling for the entire indicator between Colored (default) and Monochrome.
* Color Candles: Plots candles based on the internal & swing structures from within the indicator on the chart.
* Internal Structure: Displays the internal structure labels & dashed lines to represent them. (BOS & CHoCH).
* Confluence Filter: Filter non-significant internal structure breakouts.
* Swing Structure: Displays the swing structure labels & solid lines on the chart (larger BOS & CHoCH labels).
* Swing Points: Displays swing points labels on chart such as HH, HL, LH, LL.
* Internal Order Blocks: Enables Internal Order Blocks & allows the user to select how many most recent Internal Order Blocks appear on the chart.
* Swing Order Blocks: Enables Swing Order Blocks & allows the user to select how many most recent Swing Order Blocks appear on the chart.
* Equal Highs & Lows: Displays EQH / EQL labels on chart for detecting equal highs & lows.
* Bars Confirmation: Allows the user to select how many bars are needed to confirm an EQH / EQL symbol on chart.
* Fair Value Gaps: Displays boxes to highlight imbalance areas on the chart.
* Auto Threshold: Filter out non-significant fair value gaps.
* Timeframe: Allows the user to select the timeframe for the Fair Value Gap detection.
* Extend FVG: Allows the user to choose how many bars to extend the Fair Value Gap boxes on the chart.
* Highs & Lows MTF: Allows the user to display previous highs & lows from daily, weekly, & monthly timeframes as significant levels.
* Premium/ Discount Zones: Allows the user to display Premium, Discount , and Equilibrium zones on the chart

## (3) CryptoLiquidity.pine

Liquidity Heatmap for 1BullBear® Team

## (4) TradeSessions.pine

Trading Sessions Indicator for 1BullBear® Concept.

Defaults are set to 🇹🇭 Thailand Timezone (UTC +7).

TIMEZONE : 7
SESSION A : NEW YORK | 19:30 - 20:00
SESSION B : LONDON | 20:00 - 20:00
SESSION C : TOKYO | 20:00 - 20:00

Change your chart and so not change the settings.
It should automatically correct the plotting.

**Added**
+ Previous Day High (PDH)
+ Previous Day Low (PDL)
+ Previous Week High (PWH)
+ Previous Week High (PWL)*
+ Currency Strength
+ Session Clock
+ PDHL/ PWHL/ PMHL logic updated
