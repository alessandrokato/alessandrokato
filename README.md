# Alessandro Kato — Turning Messy Information Into Usable Decisions

**MSc Business Information Management (RSM, Erasmus University) · Background in International Business**
Focus: business intelligence, commercial analytics, financial analysis, data quality, and energy-market research.

I work at one consistent problem, in two forms: **how a constrained resource becomes usable.** In data, that means turning fragmented business information into decisions. In energy, it means understanding what makes power dense, reliable, and affordable enough to depend on. The projects below are different points on that same line.

---

## The Idea Behind the Work

A short version of a thought that connects everything here.

A sense is not a recording of the world — it is a *prediction* about the next moment, accurate enough to act on. Touch warns you a thing is on you; sight warns you it is across the valley. Same function, longer range. Planning a quarter ahead is that same function, run further out in time.

But prediction is not free. It runs on energy — the brain is ~2% of body weight yet burns ~20% of the body's energy. Foresight is expensive, so the reach of any system's foresight is capped by the energy it can afford.

That single rule connects the two things I work on. **Data is the foresight end** — turning information into better predictions for a decision. **Energy is the cost end** — the resource every prediction, in a brain, a company, or a power grid, actually runs on. Documentation, dashboards, and analytics are how organizations extend their foresight beyond any individual; energy systems are what make that foresight affordable at scale.

The full essay is on LinkedIn. This repository is the evidence.

---

## Portfolio

### 1. Industrial Market Prioritization Dashboard
**Stack:** Power BI · SQL · weighted scoring model · synthetic (non-confidential) data
**Repo:** https://github.com/alessandrokato/industrial-market-prioritization-dashboard

A decision-support dashboard that turns business criteria into segment rankings, factor breakdowns, scenario views, and recommendation outputs. SQL logic handles joins, weighted scoring, opportunity ranking, and factor aggregation; the Power BI layer makes the result interpretable for stakeholders.

**What it demonstrates:** translating fuzzy commercial questions into a structured, defensible prioritization framework — the analyst's core job of making messy reality decidable. Built from real experience structuring fragmented commercial data (500+ companies, 100+ case files) during a market-intelligence internship, rebuilt here on synthetic data.

### 2. Renewable Energy FP&A / Business Control Model
**Stack:** Excel · Power Query · PivotTables · variance analysis · scenario modelling · synthetic portfolio data
**Repo:** https://github.com/alessandrokato/renewable-energy-fpna-performance-model

A monthly performance model for a renewable-energy asset portfolio: actual vs. budget vs. forecast across revenue, OpEx, EBITDA, production volume, utilization, and downtime, with variance analysis and scenario assumptions feeding a management dashboard.

**What it demonstrates:** financial decision-support at the energy layer — the same "make it usable for a decision" instinct applied to power-generation economics rather than commercial data. This project is where the data interest reaches down into energy, the bridge between the two halves of the portfolio.

### 3. Energy-Market Thesis *(in progress)*
**Stack:** R · interrupted time-series analysis · HAC robust standard errors · multi-source data pipeline (SMARD, ENTSO-E, gas and carbon proxies)

I am currently completing my MSc thesis on Germany's nuclear phase-out and its effect on day-ahead electricity-price outcomes, built on a cleaned, validated ~4,000-day, 66-variable market dataset. The framing: a power grid is itself a forecasting system, balancing supply against predicted demand — and the thesis examines what happens to that balance when a dense, stable source is removed.

**What it demonstrates:** end-to-end empirical work — building an analysis-ready dataset from inconsistent sources (timestamp alignment, missingness and duplicate checks, treatment-design audits) and applying a defensible econometric design to a real policy question.

---

## Skills & Concepts Demonstrated

**Analytics & BI:** Power BI, SQL, Excel (Power Query, PivotTables), dashboarding, KPI reporting, decision support, data quality, data cleaning, weighted scoring, scenario analysis.

**Finance & FP&A:** variance analysis, actual-vs-budget-vs-forecast modelling, EBITDA/OpEx/revenue tracking, financial decision support.

**Data & research:** R, time-series analysis, multi-source data pipelines, source validation, reproducible cleaning and aggregation, econometric design.

**Domain:** market intelligence, commercial prioritization, energy markets, electricity-price dynamics, digital transformation.

**Working style:** finding the usable signal inside messy, constrained information — and tracing a problem down to the constraint that actually governs the outcome.

---

*These projects use synthetic or non-confidential data and are built to demonstrate method and reasoning, not to expose proprietary information. The connecting essay is on [LinkedIn](https://www.linkedin.com/in/alessandrokato/).*
