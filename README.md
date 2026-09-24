# Ng Cheng Xin

### Data Analytics | Geospatial Optimisation | Forecasting & Data Pipelines

I'm a final-year Computer Science (Data Analytics) student at **Asia Pacific University** in Kuala Lumpur, graduating October 2026.

Most of my work sits where messy real-world data has to become a decision someone can defend. My final year project takes five public datasets — vehicle registrations, census population, points of interest, charging station locations — and turns them into a map of who in the Klang Valley is being left behind by commercially-driven EV charging, plus a specific list of twenty sites that would address it. Before that I spent five months in revenue assurance at a cross-border payments company, automating the reconciliation lifecycle between internal transaction logs and partner statements arriving in 30+ different formats.

What I care about most is testing my own work. On my FYP I re-ran a comparison from my own interim report under proper validation and found my earlier conclusion was an artefact of a single train-test split — so I reported the reversal rather than keeping the better-looking result. I also report the one hypothesis test that failed, and the structural reason it couldn't have succeeded.

---

## Technical Skills

**Programming** — Python · R · SQL · Java · JavaScript
**Data & ML** — pandas · NumPy · scikit-learn · XGBoost · LightGBM · GeoPandas · H3 · Prophet · statsmodels
**BI & Visualisation** — Power BI · Tableau · Streamlit · Plotly · SAS Viya
**Platforms** — Microsoft Fabric · Power Automate · Power Apps · SharePoint · Git

---

## Featured Projects

### 🗺️ Equitable EV Charging Infrastructure Planning — Final Year Project
**[`fyp-system`](https://github.com/Ansonng0213/fyp-system)**

A geospatial decision-support system for EV charging placement across the Greater Klang Valley — measuring where access is missing, explaining why the market doesn't go there, and prescribing where new stations should go.

- 13-stage pipeline over 5 open data sources; 4,003 H3 hexagons scored on a Charging Desert Index
- 21 model builds across 4 streams; 6 forecasting families under 980 rolling-origin validation tests
- 5 classifiers under spatial block cross-validation — 0.51 PR-AUC against a 0.055 base rate
- Equity-optimised siting reaches **1,052,353 residents**; market-predicted siting reaches **8,755** — zero overlap between the two lists
- Deployed as an 8-page Streamlit dashboard with live what-if simulation

`Python` · `GeoPandas` · `H3` · `scikit-learn` · `XGBoost` · `Prophet` · `Streamlit`

---

### ⚡ LUCID — Smart Grid Intelligence
🏆 **SAS Hackathon 2025 — Global Champion, Energy Track**

Hourly electricity demand forecasting on continuous IoT grid sensor data, benchmarking 6 time-series approaches in SAS Viya Model Studio to a champion model at **12.8% WMAPE**. Contributed to unsupervised anomaly detection across 6 fault categories and to constraint-based dispatch optimisation across grid and renewable supply.

One of 10 team members. Won the Energy Track globally against 100+ competing teams and presented at SAS headquarters to SAS Asia Pacific leadership.

`SAS Viya` · `SAS Optimization` · `Python`

---

## Achievements

- 🥇 **SAS Hackathon 2025** — Global Champion, Energy Track
- 🏅 **UMDAC Datathon 2024** — Finalist

---

## Contact

📧 ansonng0213@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/ng-cheng-xin-363692295/)
