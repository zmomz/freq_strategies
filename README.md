# Frequency Trading Strategies for Freqtrade

This repository contains various Python-based algorithmic trading strategies specifically designed for use with [Freqtrade](https://www.freqtrade.io/), an open-source cryptocurrency trading bot.

## Objective

- Provide diverse and effective trading strategies for cryptocurrency markets.
- Facilitate easy integration and deployment within the Freqtrade trading bot environment.
- Enable efficient backtesting, optimization, and live trading.

## Repository Contents

| Script Name                    | Description                                           |
|--------------------------------|-------------------------------------------------------|
| ClucMay72018.py                | Strategy based on specific market conditions.          |
| CombinedBinHAndClucV8.py       | Combines BinH and Cluc strategies (version 8).         |
| CombinedBinHAndClucV8Hyper.py  | Hyper-optimized BinH and Cluc strategies.              |
| CombinedBinHClucAndMADV6.py    | Combines BinH, Cluc, and MAD strategies (version 6).   |
| Combined_NFIv6_SMA.py          | Nostalgia For Infinity strategy combined with SMA.     |
| Dyna_opti.py                   | Dynamic optimization strategy.                         |
| ElliotV8_original_ichiv3.py    | Elliott wave strategy using Ichimoku indicators.       |
| MacheteV8b.py                  | Machete strategy, version 8b.                          |
| MarketStructureCHOCH.py        | Strategy focused on Change of Character (CHOCH).       |
| MarketStructureSFP.py          | Targets Swing Failure Patterns (SFP).                  |
| NASOSv4.py                     | NASOS strategy, version 4.                             |
| NASOSv5_mod3.py                | Modified version of NASOS strategy version 5.          |
| NFI5MOHO_WIP.py                | Combined NFI and MOHO logic (work in progress).        |
| NostalgiaForInfinityX4.py      | Nostalgia For Infinity strategy, version 4.            |
| RalliV1.py                     | Initial Ralli trading strategy.                        |
| RalliV1_disable56.py           | Modified Ralli strategy version 1.                     |
| SMAOffset.py                   | SMA-based offset strategy.                             |
| SMAOffsetProtectOptV1.py       | Optimized SMA strategy with protective mechanisms.     |
| SMAOffsetV2.py                 | Enhanced SMA offset strategy, version 2.               |
| TrendLines.py                  | Strategy using trendline analysis.                     |
| compactedFUOPT.py              | Compact fully optimized strategy.                      |
| stoploss.py                    | Script for managing stop-loss parameters.              |

## Getting Started

### 1. Install Freqtrade
Follow instructions to install Freqtrade:

- [Freqtrade Installation Guide](https://www.freqtrade.io/en/latest/installation/)

### 2. Clone this repository
```bash
git clone https://github.com/zmomz/freq_strategies.git
cd freq_strategies
```

### 3. Using the Strategies

Copy desired strategy scripts into your Freqtrade strategies folder:

```bash
cp strategies/*.py ~/freqtrade/user_data/strategies/
```

Run backtests or deploy strategies live with Freqtrade:

```bash
freqtrade backtesting --strategy YourStrategyName
freqtrade trade --strategy YourStrategyName
```

## Contributions

Feel free to submit issues or pull requests to enhance these strategies.

## License

This repository is provided under the MIT License. See the [LICENSE](LICENSE) file for details.

