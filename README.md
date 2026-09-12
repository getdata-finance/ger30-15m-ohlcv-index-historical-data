# GER30 15m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-304_782_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 15m OHLCV index historical data** — ultra high-quality 15m OHLCV for **DAX 40 (GER30)**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **304,782** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `GER30_15m.csv` (10,102 rows, `2026-03-12` -> `2026-09-11`, 923.48 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **304,782** `15m` rows (full `1m`: 2,329,742), **11 timeframes**, `2008-09-10` -> `2026-09-11`.

## Download sample

**[GER30_15m.csv](https://github.com/getdata-finance/ger30-15m-ohlcv-index-historical-data/blob/main/GER30_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-15m-ohlcv-index-historical-data/main/GER30_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-15m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-15m-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-15m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 10,102 | **304,782** |
| Size | 923.48 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Period | `2026-03-12` -> `2026-09-11` | `2008-09-10` -> `2026-09-11` |
| File | `GER30_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/ger30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T02:30:00+00:00 | 23316.29 | 23320.06 | 23250.05 | 23269.3 | 1231 |
| 2026-03-12T02:45:00+00:00 | 23269.3 | 23276.05 | 23244.3 | 23251.29 | 1258 |
| 2026-03-12T03:00:00+00:00 | 23251.29 | 23272.31 | 23236.3 | 23239.31 | 1020 |
| 2026-03-12T03:15:00+00:00 | 23239.31 | 23246.04 | 23222.3 | 23227.29 | 947 |
| 2026-03-12T03:30:00+00:00 | 23227.29 | 23232.56 | 23205.31 | 23219.31 | 1080 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T18:45:00+00:00 | 25546.65 | 25550.65 | 25541.64 | 25545.65 | 582 |
| 2026-09-11T19:00:00+00:00 | 25545.65 | 25550.66 | 25542.64 | 25550.65 | 597 |
| 2026-09-11T19:15:00+00:00 | 25550.65 | 25553.15 | 25546.66 | 25547.65 | 677 |
| 2026-09-11T19:30:00+00:00 | 25547.65 | 25550.66 | 25544.64 | 25547.65 | 529 |
| 2026-09-11T19:45:00+00:00 | 25547.65 | 25558.15 | 25540.64 | 25553.89 | 989 |

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

df = pd.read_csv('GER30_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_15m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GER30_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **304,782** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30)*
