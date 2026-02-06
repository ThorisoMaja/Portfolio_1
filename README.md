This repository contains an interactive Power BI dashboard built using a Walmart retail sales dataset. The goal of this project is to analyze sales performance across different branches, time periods to uncover insights that support data‑driven decision‑making.
Tools & Technologies

Power BI Desktop – Data modeling, DAX, report building
Microsoft Excel / CSV – Data preprocessing 
Data Analysis Expressions (DAX) – Measures & calculated columns
GitHub – Version control and project documentation

(High‑Level)
Overall Trend & Seasonality

Sales rise from January and peak around April–June, then soften in late summer, recover in September–October, and ease into November–December.
The pattern indicates spring/early‑summer strength and a late‑year cool‑down, suggesting seasonality that does not strictly mirror temperatures.

Quarterly Performance

Best‑performing quarter in the period shown: 2010 Q3 (~$0.71bn).
2011 remains relatively stable across quarters (~$0.59–$0.68bn).
2012 Q1 appears lower (~$0.18bn), likely partial data (be explicit about coverage in the README).

Holidays vs Non‑Holidays

Total sales are much larger on non‑holiday days (~$1.05bn) vs holiday days (~$0.52bn)—expected, since non‑holiday days vastly outnumber holiday days.
Action: Consider comparing average per day (or per week) to measure lift on holiday periods; totals alone understate holiday impact.

Fuel Price

Fuel prices peak around May (~$3.2–$3.3) and trend down into year‑end.
Scatter of Sales vs Fuel Price shows no strong linear relationship—sales occur across the fuel price range.
Interpretation: Any fuel‑price effect may be second‑order or confounded (e.g., promotions, seasonality, store mix).

Unemployment

Unemployment declines from ~8.3% (2010) to sub‑8% (2011) in your view.
The Sales vs Unemployment scatter shows weak/indistinct correlation—high and low sales appear across the 6–10% range.
Conclusion: At this aggregation level, macro labor conditions aren’t a primary driver of monthly sales variance.

Temperature

Average temperature peaks in mid‑year, but sales do not strictly follow; some of the strongest sales occur before/after the hottest months.
This hints at category mix or calendar effects (back‑to‑school, end‑of‑season promotions) dominating simple weather impacts.

Store/Branch Variation

The monthly chart indicates noticeable variation by store/branch across months (leadership flips month‑to‑month).
Action: Rank stores by share of period sales, YoY trajectory, and volatility to isolate under/over‑performers.


