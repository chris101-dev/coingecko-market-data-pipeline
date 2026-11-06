# CoinGecko Market Data Pipeline

A portfolio MVP for a scheduled batch pipeline using CoinGecko market data.
The project is intended to demonstrate Python ingestion, Airflow orchestration,
SQL modeling, data quality checks, and basic data governance.

## Initial scope

- Fetch market snapshots for a small, selected set of coins.
- Preserve the source response and ingestion metadata.
- Normalize the market observations and load them idempotently.
- Validate the data and report pipeline-run results.

This project uses aggregated market data; it does not represent exchange
transactions or trades. Implementation and run instructions will be added as
the MVP is built.
