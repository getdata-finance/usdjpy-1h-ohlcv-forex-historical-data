# USDJPY 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-153_464_rows-blue)](https://getdata.finance/datasets/usdjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdjpy)

### -> [**Download the full USDJPY dataset on getdata.finance**](https://getdata.finance/datasets/usdjpy)

**USDJPY 1h OHLCV forex historical data** — ultra high-quality 1h OHLCV for **US Dollar / Japanese Yen**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdjpy) · **153,464** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `USDJPY_1h.csv` (3,120 rows, `2026-02-01` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdjpy)** — **153,464** `1m` rows (~14.40 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2001-11-28` -> `2026-07-31`.

## Download sample

**[USDJPY_1h.csv](https://github.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/blob/main/USDJPY_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/main/USDJPY_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdjpy-1h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdjpy-1h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdjpy-1h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdjpy](https://getdata.finance/datasets/usdjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdjpy))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `1h` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 3,120 | **153,464** |
| Size | 0.32 MB | ~14.40 MB |
| Period | `2026-02-01` -> `2026-07-31` | `2001-11-28` -> `2026-07-31` |
| File | `USDJPY_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Coverage report | — | [USDJPY coverage](https://getdata.finance/coverage/usdjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdjpy)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/usdjpy) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-01T22:00:00+00:00 | 156.031 | 156.547 | 155.883 | 156.382 | 2888.1950916588 |
| 2026-02-01T23:00:00+00:00 | 156.382 | 156.666 | 156.231 | 156.374 | 19086 |
| 2026-02-02T00:00:00+00:00 | 156.374 | 156.423 | 155.974 | 156.383 | 24635 |
| 2026-02-02T01:00:00+00:00 | 156.383 | 156.54 | 156.16 | 156.189 | 18953 |
| 2026-02-02T02:00:00+00:00 | 156.189 | 156.293 | 155.998 | 156.293 | 15833 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T16:00:00+00:00 | 159.881 | 160.082 | 159.837 | 160.081 | 9293 |
| 2026-07-31T17:00:00+00:00 | 160.081 | 160.216 | 158.874 | 159.223 | 39303 |
| 2026-07-31T18:00:00+00:00 | 159.223 | 159.84 | 159.022 | 159.608 | 20501 |
| 2026-07-31T19:00:00+00:00 | 159.608 | 159.945 | 159.589 | 159.889 | 10095 |
| 2026-07-31T20:00:00+00:00 | 159.889 | 159.911 | 157.957 | 158.181 | 49984 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[getdata.finance](https://getdata.finance/datasets/usdjpy)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **153,464** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full USDJPY dataset on getdata.finance](https://getdata.finance/datasets/usdjpy)**

---
*GetData · USDJPY 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdjpy) · 2026-08-05 UTC*
