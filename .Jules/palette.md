## 2024-07-21 - [Colorblind-Friendly Plotting in Jupyter Notebooks]
**Learning:** Using purely color-based coding in notebook plots can make them inaccessible for colorblind users. It is much more readable and accessible to use distinct markers and line styles (such as circles with solid lines vs crosses with dashed lines) to distinguish training vs. validation metrics or different classes.
**Action:** Always combine distinguishable markers (`o`, `x`) and line-styles (`-`, `--`) in matplotlib plots when showing multiple lines (e.g., train vs. validation) in Jupyter Notebooks.
