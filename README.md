# DE Data Platform
A Data Engineering pet project focused on building an end-to-end data platform that integrates multiple product databases into a unified analytics layer using Docker, Airflow, dbt, and modern data technologies.


## Project Overview

The platform simulates a company operating multiple software products, each with its own database schema and business logic. The goal is to build a reliable data pipeline that extracts, transforms, and consolidates data from these sources for analytics and reporting.

## Architecture

The platform will integrate the following data sources:

* **PayFlow** — a payment processing product backed by PostgreSQL.
* **Subscriptly** — a subscription billing product backed by PostgreSQL.
* **DocPay** — a planned document-oriented data source, to be introduced in a later phase.

The central data platform will orchestrate ingestion, transformations, and analytical data modeling.

## Technology Stack

* Docker & Docker Compose
* PostgreSQL
* SQL and Python
* Apache Airflow — workflow orchestration
* dbt — data transformation and modeling
* Data warehouse — centralized analytical storage
* Object storage — raw data storage
