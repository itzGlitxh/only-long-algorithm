# Only-Long Day Trading Algorithm

## Overview
The Only-Long Day Trading Algorithm is designed for day trading stocks, focusing exclusively on long positions. This strategy utilizes a combination of advanced technical indicators to identify bullish market conditions and execute trades effectively.

### Strategy Highlights
- **Indicators Used**:
  - **Relative Momentum Index (RMI)**: Measures momentum by comparing the magnitude of recent gains to recent losses.
  - **Average Directional Index (ADX)**: Indicates the strength of a trend.
  - **Relative Strength Index (RSI)**: Identifies overbought or oversold conditions.
  - **Ichimoku Cloud**: Provides support and resistance levels, trend direction, and momentum.

- **Execution Logic**:
  - Enters long positions based on bullish conditions indicated by RMI, ADX, RSI, and Ichimoku.
  - Uses dynamic stop-loss and take-profit levels to manage risk and lock in profits.

- **Pyramiding**: The strategy allows for multiple entries in a single direction (long) to maximize potential gains.

- **Initial Capital**: Set to $10,000, with each trade utilizing $1,000.

## Features
- **Customizable Parameters**: Easily adjust the parameters for RMI, ADX, RSI, Ichimoku, stop-loss, and take-profit levels.
- **Real-Time Alerts**: The script provides real-time entry and exit signals on the TradingView platform.
- **Visualization**: Includes visual indicators on the chart for better decision-making.

## Installation
1. Open TradingView and create a new Pine Script.
2. Copy and paste the Only-Long algorithm code into the script editor.
3. Save the script and add it to your chart.
4. Adjust the settings as desired in the input menu.

## Usage
- This algorithm is designed for intraday trading on short timeframes (e.g., 1-minute, 5-minute charts).
- Monitor the performance and make adjustments to parameters as needed based on market conditions.

## Disclaimer
This algorithm is for educational purposes only. Trading stocks involves risk, and it's important to conduct thorough research and consider your financial situation before making any trading decisions. The creator of this algorithm is not responsible for any losses incurred from its use.

## License
This project is licensed under the MIT License.

Copyright (c) 2024 Harsh Choksi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

2. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments
- Inspired by various technical analysis strategies and trading systems.
- Developed with the intention of helping traders utilize technical indicators effectively.

## Contact
For any inquiries or feedback, please reach out to harshchoksi21@gmail.com or itzGlitxh on Github.
