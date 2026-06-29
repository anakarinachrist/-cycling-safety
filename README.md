# Cycling Safety BCR Tool

An interactive, browser-based decision-support tool for comparing cycling safety interventions through a Benefit–Cost Ratio (BCR) framework. Developed as part of a PhD thesis at Instituto Superior Técnico, Universidade de Lisboa.

🔗 **Live tool:** https://your-username.github.io/cycling-safety/

## What it does

The tool combines three components to support the comparison of cycling safety interventions at the grid-cell level:

- A **crash-frequency baseline**, estimated from a Poisson–Tweedie model calibrated for Lisbon (2015–2019)
- **Literature-based safety effects** for 15 cycling infrastructure interventions, each with a reported 95% confidence interval
- **Implementation costs**, classified by evidentiary basis (itemised, decomposed, or adapted)

For any selected grid cell (or combination of cells), the tool lets you build intervention scenarios, combine multiple measures, and compare them side by side through cost, expected accident reduction, monetised benefit, and BCR — including a BCR range that reflects the uncertainty in the underlying safety-effect and cost evidence.

## Key features

- 📍 Interactive map with 2,439 grid cells across Lisbon, shaded by baseline crash frequency
- 🛠️ Catalogue of 15 cycling safety interventions with documented safety effects and costs
- 📊 Scenario comparison: build, name, and compare multiple intervention scenarios
- 📈 BCR range alongside the point estimate, to expose sensitivity to underlying uncertainty
- 💶 Cost-override: replace default unit costs with locally sourced procurement prices
- 📂 Baseline import: load a different city's crash and infrastructure dataset (same structure as Lisbon's)
- 📤 Export results to CSV, including methodological notes

## How to use it

1. Open the [live tool](https://your-username.github.io/cycling-safety/) in any modern browser (requires an internet connection, for the map tiles and charts)
2. Click a grid cell on the map to select it (Ctrl+click to select several)
3. Choose an intervention from the catalogue and set a quantity
4. Add one or more measures to build a scenario, then name and finish it
5. Compare finished scenarios as cards, in the technical results table, and in the accompanying charts

No installation is required — the tool is a single, self-contained HTML file.

## Running it locally

Download `index.html` and open it directly in a browser. An internet connection is still required, since the map (Leaflet/OpenStreetMap) and charts (Chart.js) are loaded from public CDNs.

## Methodological background

This tool was developed as part of the PhD thesis *"A Decision Support Tool for Cycling Safety Interventions: From Accident Data to Cost–Benefit Evaluation"*. The full methodology, including the crash-frequency model, the intervention-effect literature review, and the cost–benefit framework, is documented in the thesis itself.

## How to cite

If you use this tool in academic work, planning practice, or any other context, please cite it as:

> Ana Karina de Barros Christ (2026). *Cycling Safety BCR Tool: An Interactive Decision-Support Tool for Cycling Safety Interventions*. PhD thesis, Instituto Superior Técnico, Universidade de Lisboa. Available at: https://github.com/your-username/cycling-safety

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. While the license does not legally require it, citation is greatly appreciated (see above).

## Author

Ana Karina de Barros Christ — PhD candidate, Instituto Superior Técnico, Universidade de Lisboa
Supervised by  Prof. Carlos Roque and Prof. Filipe Moura
