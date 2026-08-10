TravelSphere European Hotel Performance Dashboard

Tableau Desktop | Data Visualisation | Business Intelligence

Overview

TravelSphere is a simulated luxury travel agency case study. The business problem: TravelSphere wants to expand into new European markets but has no structured way to know which cities and hotels are worth partnering with, or what drives guest satisfaction across different traveller segments. This project solves that by taking a raw dataset of 155,861+ real hotel reviews across 6 European cities and turning it into an interactive tool the team could actually use, not just a static report.

The build went from messy, unstructured review text to a fully interactive 3-dashboard Tableau suite. Along the way, I engineered custom metrics like an "Expectation Gap Score" to catch dissatisfaction a simple average rating would miss, and used Python to extract sentiment themes from raw review text so the dashboard could show why customers were happy or unhappy, not just whether they were.

What it does
3 interactive dashboards: KPIs, geographic performance, nationality bias, sentiment drivers, city rankings, traveller type, seasonal trends
10+ calculated fields, including the custom Expectation Gap Score
Python and AI -based sentiment theme extraction from unstructured review text
7 visualisation types (geographic bubble map, lollipop chart, heatmap, diverging bar chart) with consistent colour coding and cross-panel filtering
Key finding

The dashboard surfaced a specific, non-obvious insight: business travellers in London during summer were significantly less satisfied than their review scores implied (-3.15 Expectation Gap Score) — the basis for a concrete recommendation on which cities to target in a UK marketing campaign. Vienna ranked as the top-performing city overall (8.57 average review score).

Tools used

Tableau Desktop, Tableau Prep, Python with AI
