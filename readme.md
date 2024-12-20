# Crypto Historical Price Data (2010-2024)

This repository contains historical Crypto price data from 2010 to 2024 in CSV format. The dataset provides detailed pricing information, including opening, closing, high, and low prices, as well as additional data such as volume and market cap.

## Contents

The repository includes the following file:

- **2010.csv -> 2024.csv**  
  This file contains Crypto price data from 2010 onward (the data may be available for a partial or full range depending on the year) with the following columns:

| Column      | Description |
|-------------|-------------|
| `timeOpen`  | The timestamp of the opening price. |
| `timeClose` | The timestamp of the closing price. |
| `timeHigh`  | The timestamp when the highest price occurred on that day. |
| `timeLow`   | The timestamp when the lowest price occurred on that day. |
| `name`      | A unique identifier for the specific data entry (could be a date or other identifier). |
| `open`      | The opening price (in USD). |
| `high`      | The highest price on that day (in USD). |
| `low`       | The lowest price on that day (in USD). |
| `close`     | The closing price (in USD). |
| `volume`    | The volume traded during the period (in BTC). |
| `marketCap` | The market capitalization (in USD). |
| `timestamp` | The timestamp of the record, typically reflecting the end of the day. |
