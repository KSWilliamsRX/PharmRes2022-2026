# PharmRes2022-2026
Sankey for pharmacy residency match rates 
ASHP Pharmacy Residency Match — Interactive Sankey Diagram
Interactive visualization of ASHP PGY1 and PGY2 pharmacy residency match data (2022–2026), showing applicant flows by state and school, position fill rates by specialty, and year-over-year trends.
Live Demo
View the visualization →
Features

Year toggle across 5 years of match data (2022–2026)
PGY1 Sankey flow: Applicants by state → matched/unmatched/withdrew → position types filled/unfilled
PGY2 Sankey flow: Positions → specialty categories → filled/unfilled per specialty with fill rate percentages
School-level detail: Click any state to see individual school data with 5-year sparkline trends
YoY tooltips: Hover any node for year-over-year comparisons with directional indicators
Draggable nodes: Reposition any node and links update in real time

Data Sources
All data is sourced from publicly available ASHP Resident Matching Program statistics published by National Matching Services Inc.:

ASHP Match Statistics
PGY1 Applicants by School reports (Phase I for 2026; Combined Phase I & II for 2022–2025)
Summary of Programs and Positions Offered and Filled reports

Important note: 2026 data reflects Phase I results only. Phase II results are not yet available. Prior years (2022–2025) reflect combined Phase I and Phase II data. Direct year-over-year comparisons with 2026 should account for this difference.
Built With

D3.js v7 — data visualization library
d3-sankey v0.12 — Sankey diagram layout
Claude (Anthropic) — AI-assisted development of the visualization code, data compilation, and iterative design

Attribution
This visualization was developed with the assistance of Claude, an AI assistant by Anthropic. Claude was used to:

Retrieve and compile match statistics from ASHP/NMS PDF reports across five years
Generate the D3.js/d3-sankey visualization code
Iteratively refine the layout, interactivity, and design based on feedback

