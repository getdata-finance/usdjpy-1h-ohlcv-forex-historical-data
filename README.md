# USDJPY 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-154_118_rows-blue)](https://getdata.finance/datasets/usdjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdjpy)

### -> [**Download the full USDJPY dataset on getdata.finance**](https://getdata.finance/datasets/usdjpy)

**USDJPY 1h OHLCV forex historical data** — ultra high-quality 1h OHLCV for **US Dollar / Japanese Yen**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **US Dollar / Japanese Yen** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdjpy) · **154,118** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `USDJPY_1h.csv` (3,128 rows, `2026-03-10` -> `2026-09-09`, 309.03 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdjpy)** — **154,118** `1h` rows (full `1m`: 9,184,987), **11 timeframes**, `2001-11-28` -> `2026-09-09`.

## Download sample

**[USDJPY_1h.csv](https://github.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/blob/main/USDJPY_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/main/USDJPY_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdjpy-1h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdjpy-1h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdjpy](https://getdata.finance/datasets/usdjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdjpy))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 3,128 | **154,118** |
| Size | 309.03 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Period | `2026-03-10` -> `2026-09-09` | `2001-11-28` -> `2026-09-09` |
| File | `USDJPY_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Coverage report | — | [USDJPY coverage](https://getdata.finance/coverage/usdjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdjpy)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/usdjpy) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 158.978 | 159.235 | 158.958 | 159.142 | 16344 |
| 2026-03-10T20:00:00+00:00 | 159.142 | 159.2 | 159.084 | 159.146 | 5017 |
| 2026-03-10T21:00:00+00:00 | 159.146 | 159.203 | 159.124 | 159.191 | 570.8866 |
| 2026-03-10T22:00:00+00:00 | 159.191 | 159.292 | 159.162 | 159.275 | 2059 |
| 2026-03-10T23:00:00+00:00 | 159.275 | 159.296 | 159.165 | 159.215 | 5523 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T22:00:00+00:00 | 153.857 | 153.977 | 153.628 | 153.732 | 3570 |
| 2026-09-08T23:00:00+00:00 | 153.732 | 153.733 | 153.425 | 153.451 | 12295 |
| 2026-09-09T00:00:00+00:00 | 153.451 | 153.738 | 153.252 | 153.571 | 28711 |
| 2026-09-09T01:00:00+00:00 | 153.571 | 153.831 | 153.543 | 153.552 | 21036 |
| 2026-09-09T02:00:00+00:00 | 153.552 | 153.56 | 153.542 | 153.56 | 172 |

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

df = pd.read_csv('USDJPY_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDJPY_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USDJPY_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[getdata.finance](https://getdata.finance/datasets/usdjpy)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **154,118** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full USDJPY dataset on getdata.finance](https://getdata.finance/datasets/usdjpy)**

---
*GetData · USDJPY 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdjpy)*
