<div align="center">

# Stuart Douglas

**Pricing Strategy · Revenue Growth Management · Commercial Analytics**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stuartdouglas87/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@stuartdouglas79)

</div>

---

### About

I lead pricing strategy and commercial analytics for a global engineering business, and I build the tools underneath it. It's engineered-to-order: BOMs created daily, varying metallurgy, custom sizing, no two orders identical. I've worked the other end of it too, high volume and standard parts. Most pricing problems aren't technology problems: they're governance, discipline and adoption problems. The technology just makes the fix scalable.

The repositories here are working examples of that. Small, documented, reproducible tools that solve a specific commercial problem end to end.

🌐 **[sdouglas8787.github.io](https://sdouglas8787.github.io)** · 📧 **stuartdouglas79@gmail.com**

---

## What I Work On

| Area | Detail |
|------|--------|
| **Pricing governance** | Gross-to-Net waterfalls, discount corridors, price realisation measurement, delegation of authority controls |
| **Revenue growth management** | Trade terms structure, conditional vs unconditional spend, promotional attainment, PVM |
| **Commercial analytics** | Transaction-level margin analysis, customer and channel profitability, revenue bridge reporting. Engineered-to-order and high-volume standard parts |
| **Data engineering** | ETL pipelines across ERP systems, parent-to-component BOM expansion, external API integration, curated datasets for self-service reporting |
| **Forecasting** | Macroeconomic indicator pipelines, backtested forecast models, scenario and budget planning |

---

## Technical

| Category | Tools |
|----------|-------|
| **Languages** | Python, SQL, DAX, Power Query M |
| **Data** | Pandas, NumPy, PySpark, Databricks |
| **Reporting** | Power BI, Matplotlib, Plotly |
| **Platforms** | Azure, SAP, Git |

---

## Projects

| Project | What it does |
|---------|--------------|
| [input_cost_tracker](https://github.com/sdouglas8787/input_cost_tracker) | UK input costs and pass-through from ONS producer price data. Rule-generated monthly reading, self-validation against the published bulletin, and explicit statements of what the data will and will not support |
| [macro_chartbook](https://github.com/sdouglas8787/macro_chartbook) | Designed one-page UK macro readout from public ONS and FRED series. Rule-generated executive summary, YoY / rolling-12 / Wtd-R12 / CAGR battery, source and vintage on every chart |
| [motorcycle_sales_forecast](https://github.com/sdouglas8787/motorcycle_sales_forecast) | UK motorcycle registrations forecast from ~80 scraped MCIA press PDFs and Met Office data. Rolling backtest: OLS 10.3% MAPE against SARIMAX 14.6% and seasonal naive 23.0%. Weather tested and mostly rejected |
| [uk_stock_tracker](https://github.com/sdouglas8787/uk_stock_tracker) | Multi-retailer stock and price monitor: one consistent reading from eleven sources that each publish differently, every reading labelled with the route it came from |
| [team_kanban_tracker](https://github.com/sdouglas8787/team_kanban_tracker) | Excel Kanban workbook built by script: one task list, a board and team summary that build themselves |
| [g2n_waterfall](https://github.com/sdouglas8787/g2n_waterfall) | Gross-to-net and PVM bridges. Trade terms, conditional vs unconditional spend, attainment, YoY price growth. Built so it can't quietly stop adding up, and so anything it can't explain gets shown rather than buried |
| [home_energy_tariff_tracker](https://github.com/sdouglas8787/home_energy_tariff_tracker) | Forecasting engine for household energy costs. Walk-forward backtesting, bias correction, Monte Carlo tariff comparison and weather normalisation |
| [weather_dashboard](https://github.com/sdouglas8787/weather_dashboard) | End to end pipeline: API ingestion, automated processing and Power BI reporting |
| [fx_watchlist_v2](https://github.com/sdouglas8787/fx_watchlist_v2) | FX rate monitoring and alerting pipeline |

---

## Writing

**[I nearly made a £421 mistake on my energy tariff. So I built my own forecasting engine.](https://medium.com/@stuartdouglas79/i-nearly-made-a-421-mistake-on-my-energy-tariff-so-i-built-my-own-forecasting-engine-0203a8a535e6?source=friends_link&sk=7e9fadddd3d08a86adf1583a9868db44)**  
Every comparison site got it wrong because none of them knew how I actually use energy. Walk-forward validation, bias correction and Monte Carlo simulation, applied to a gas bill.
