## 2025-05-14 - Accessible Notebook Plots
**Learning:** In Jupyter Notebooks, plots often rely on default colors which can be inaccessible to colorblind users. Using distinguishable markers and line-styles (e.g., 'o-' and 'x--') ensures that different data series can be identified without relying on color.
**Action:** Always include markers and varying line-styles in multi-series plots in notebooks.

## 2025-05-14 - Interpretable Model Outputs
**Learning:** Model predictions in notebooks are often displayed as raw class indices, which are meaningless to users without checking the encoding. Using `inverse_transform` on the labels provides immediate, human-readable feedback.
**Action:** Ensure model outputs are decoded into human-readable labels before display in user-facing notebooks.
