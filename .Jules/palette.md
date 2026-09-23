## 2025-05-18 - Accessible Chart Formatting in Jupyter Notebooks
**Learning:** Default Matplotlib plots without explicit labels, titles, legends, or distinguishable markers are inaccessible to colorblind users and screen-reader users reviewing data visualizations in Jupyter Notebooks.
**Action:** Always format Matplotlib plots in notebooks with explicit `title`, `xlabel`, `ylabel`, clear `label` arguments in `plot()`, an accessible `legend()`, and distinguishable `marker` and `linestyle` parameters.
