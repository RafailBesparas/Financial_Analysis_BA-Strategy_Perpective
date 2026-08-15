# European Defence Portfolio Analytics

## Overview

This project is a learning and solution-analysis exercise exploring how market data can be transformed into useful portfolio insights.

The objective is to analyse a small universe of leading European defence companies using market data retrieved through Yahoo Finance and to structure the notebook in a way that provides a **glimpse of how the analytical logic could evolve toward a production solution**.

The selected companies are:

- BAE Systems
- Rheinmetall
- Thales
- Leonardo
- Saab

The project is not intended to provide investment advice or represent a production trading system.

## Business Problem

An investor or portfolio team needs more than historical share prices. The underlying question is:

**How can market data be transformed into a structured view of portfolio performance, risk and diversification to support better investment decisions?**

From a Solution Analyst perspective, this requires connecting the business need with the data, analytical logic and potential technology implementation.

## Solution Approach

The notebook follows a simple analytical flow:

**Yahoo Finance → Data Preparation → Currency Normalisation → Returns & Risk Analytics → Correlation → Portfolio Construction → Optimisation → Decision Insights**

Yahoo Finance is used as the primary market-data source. Because the selected securities trade in different currencies, FX data is also incorporated so that portfolio calculations can be performed using a common currency basis.

The analysis explores concepts including returns, volatility, Sharpe ratio, drawdown, Value at Risk, correlations and portfolio optimisation.

## Solution Analyst Perspective

My focus in this project is not only on producing calculations, but on understanding the relationship between:

**Business Requirement → Data → Business Rules → Analytics → Decision → Technology**

The notebook therefore acts as a prototype rather than the final solution.

In a production environment, several components would require further engineering, including automated ingestion, persistent storage, data-quality controls, logging, orchestration, monitoring, security, APIs and reporting layers.

## Value Map

![European Defence Portfolio Value Map](./assets/defence_portfolio_value_map.png)

The value map illustrates the intended relationship between available market data, analytical capabilities and the business outcomes the solution is designed to support.

## Next Steps

Future iterations could separate the notebook into reusable modules, introduce automated data-quality validation, persist processed datasets, expose analytics through APIs, schedule portfolio calculations and integrate the outputs with a reporting or decision-support interface.

The purpose is to progressively move from **analysis in a notebook toward the design of a maintainable financial analytics solution**.
