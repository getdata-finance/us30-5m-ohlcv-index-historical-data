# US30 5m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_225_800_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 5m OHLCV index historical data** — ultra high-quality 5m OHLCV for **Dow Jones 30**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **Dow Jones 30** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **1,225,800** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `US30_5m.csv` (36,126 rows, `2026-03-12` -> `2026-09-11`, 2.74 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **1,225,800** `5m` rows (full `1m`: 5,980,529), **11 timeframes**, `2009-03-11` -> `2026-09-11`.

## Download sample

**[US30_5m.csv](https://github.com/getdata-finance/us30-5m-ohlcv-index-historical-data/blob/main/US30_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-5m-ohlcv-index-historical-data/main/US30_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/us30-5m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us30-5m-ohlcv-index-historical-data/](https://getdata-finance.github.io/us30-5m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us30](https://getdata.finance/datasets/us30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Index | Dow Jones 30 · Index |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 36,126 | **1,225,800** |
| Size | 2.74 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Period | `2026-03-12` -> `2026-09-11` | `2009-03-11` -> `2026-09-11` |
| File | `US30_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/us30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T02:30:00+00:00 | 46893.65 | 46901.65 | 46868.65 | 46874.15 | 1145 |
| 2026-03-12T02:35:00+00:00 | 46874.15 | 46874.65 | 46799.65 | 46802.65 | 1542 |
| 2026-03-12T02:40:00+00:00 | 46802.65 | 46839.15 | 46786.15 | 46832.65 | 1414 |
| 2026-03-12T02:45:00+00:00 | 46832.65 | 46843.65 | 46814.15 | 46818.15 | 1225 |
| 2026-03-12T02:50:00+00:00 | 46818.15 | 46838.65 | 46804.65 | 46828.15 | 1188 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T20:20:00+00:00 | 52553.71 | 52560.21 | 52553.71 | 52558.71 | 275 |
| 2026-09-11T20:25:00+00:00 | 52558.71 | 52558.71 | 52551.71 | 52556.21 | 268 |
| 2026-09-11T20:30:00+00:00 | 52556.21 | 52564.71 | 52551.21 | 52557.21 | 362 |
| 2026-09-11T20:35:00+00:00 | 52557.21 | 52557.71 | 52550.21 | 52552.71 | 308 |
| 2026-09-11T20:40:00+00:00 | 52552.71 | 52554.71 | 52539.21 | 52550.96 | 281 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US30_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('US30_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[getdata.finance](https://getdata.finance/datasets/us30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,225,800** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**

---
*GetData · US30 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us30)*
