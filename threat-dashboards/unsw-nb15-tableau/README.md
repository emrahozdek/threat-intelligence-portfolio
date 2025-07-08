# Threat Session Analysis - UNSW NB15 Dataset
This project explores network session characteristics from the UNSW-NB15 dataset to differentiate between normal and attack behavior using visual analytics.
## Key Insights:
**Average Session Duration**: Some attacks (e.g. DoS, Fuzzers) exhibit unusually long durations.
**Bytes Sent**: Attack sessions tend to involve significantly higher data transfer in some cases.
## Dashboard Overview Includes:
- Session Count by Attack Category
- Average Session Duration
- Total Bytes Sent by Protocol

##Tools Used:
**Tableau Public**
**Python (Pandas, Polars, Altair)** for preprocessing and data export
**UNSW-NB15** dataset (Kaggle)
