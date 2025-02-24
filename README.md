# TwoCircles
A take home assessment from Two Circles.

This project covers a simple ETL and data warehouse solution for sales data. Three files exist in this project, as listed below:

  1) SQL schema
     This includes creation of three tables with fixed schema and defined index for optimal query performance. Also, a consolidated
     view that aggregates the three tables into a single table for reporting and analysis.
  2) ETL .py file
     a) extraction/ingestion from 3 .csv files (os and pandas)
     b) transformation/data cleaning (pandas)
     c) Load/push to data warehouse (sqlalchemy)
  3) DAG .py file
     Note this file is very rough and not completely configured. Since this data contains time series elements, it is safe to assume
     that a production data pipeline would include some form of scheduling.
