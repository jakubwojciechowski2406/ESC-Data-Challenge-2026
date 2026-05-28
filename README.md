# AI Adoption and Cross-Border E-Commerce in the EU

Power BI dashboard and analysis exploring the relationship between artificial intelligence adoption and cross-border e-commerce across European Union member states.

**Authors:** Jakub Wojciechowski, Antoni Staszczyk, Piotr Biesiekirski  
**Event:** External Statistics Conference 2026 Data Challenge (BIS / ECB / NBP)  
**My contribution:** Power BI dashboard, DAX measures, data visualization

---

## 1. Research question

To what extent is AI adoption associated with cross-border e-commerce performance across EU member states in a fragmented and uncertain economic environment?

## 2. Data sources

- **Eurostat — ICT usage in enterprises:** [AI adoption (≥1 technology)](https://ec.europa.eu/eurostat/databrowser/view/isoc_eb_ai/default/bar?lang=en), AI intensity (≥2 technologies)
- **Eurostat — E-commerce:** [B2C and B2B online sales](https://ec.europa.eu/eurostat/databrowser/view/isoc_ec_esels/default/table?lang=en)
- **European Central Bank (ECB):** [Daily exchange rates](https://data.ecb.europa.eu/data/datasets/EXR) — EUR/USD, EUR/GBP, EUR/CNY

## 3. Tools

- **Power BI Desktop** — interactive dashboard with multiple report pages and slicers
- **DAX** — custom measures: `AI Adoption (≥1)`, `AI Intensity (≥2)`, `E-commerce B2B`, `E-commerce B2C`, currency conversion measure

## 4. Dashboard preview

### Dashboard overview

![Dashboard](screenshots/dashboard_overview.png)

### AI adoption across EU countries

![AI Adoption Map](screenshots/ai_adoption_map.png)

A pronounced North-South / West-East gradient: digitally advanced economies (Denmark, Finland, Sweden) consistently lead, while several Central and Eastern European countries lag behind.

### AI adoption vs B2C e-commerce

![AI vs B2C scatter](screenshots/ai_vs_b2c_scatter.png)

A clear positive association between AI adoption and B2C e-commerce participation across EU member states.

### AI intensity (≥2 technologies) vs B2C e-commerce

![AI intensity vs B2C](screenshots/ai_intensity_vs_b2c_scatter.png)

The relationship remains qualitatively similar when using a stricter measure (firms using at least two AI technologies).

### B2B vs B2C e-commerce

![B2B vs B2C](screenshots/b2b_vs_b2c_chart.png)

B2C participation is consistently higher than B2B — the link between AI adoption and digital trade is stronger for consumer-facing activities.

### Evolution of B2C e-commerce in selected EU countries

![B2C evolution](screenshots/b2c_evolution_lineplot.png)

Heterogeneous development paths: Denmark and Finland lead with stable, mature levels; Romania lags despite recent growth; Poland follows an intermediate trajectory.

### Currency context vs B2C e-commerce

![Currency vs B2C](screenshots/currency_vs_b2c.png)

Cross-border e-commerce continues to grow even as the EUR weakens against major external currencies (USD, GBP, CNY), suggesting resilience of digital trade.

## 5. Key findings

- **Positive association between AI adoption and B2C e-commerce** - countries with higher AI adoption among enterprises also report a larger share of firms engaged in cross-border online consumer sales.
- **Robustness check holds:** the relationship remains qualitatively similar when using a stricter measure (AI intensity ≥ 2 technologies).
- **Weaker link for B2B e-commerce:** AI adoption is more closely related to consumer-facing digital trade than business-to-business.
- **Persistent digital fragmentation** within the EU Single Market — uneven AI diffusion may reinforce existing economic disparities.

## 6. Policy implications

- Coordinated EU-level digital policies could help broaden participation in cross-border e-commerce.
- Supporting AI diffusion among smaller firms and in lagging regions appears particularly relevant.
- Strengthening AI adoption may help build resilience in an environment marked by macroeconomic uncertainty and external shocks.

## 7. Files

- `ESC2026_Data_Challenge_PowerBI.pbix` — Power BI report (open with Power BI Desktop to interact)
- `Visualizations/` — dashboard previews
- `Docs/ESC2026_Data_Challenge_Report.pdf` — full project report
- `Docs/ESC2026_Data_Challenge_Abstract.pdf` — project abstract
- `Docs/2026_ESC_Data_Challenge_participation_certificate.pdf` - Certificate of Participation, ESC 2026 Data Challenge (BIS / ECB / NBP)

## 8. How to view interactively

1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only)
2. Open `ESC2026_Data_Challenge_PowerBI.pbix`
3. Use slicers to filter by country and year

For a quick overview without installing Power BI, see the screenshots above and the full report in `docs/report.pdf`.
