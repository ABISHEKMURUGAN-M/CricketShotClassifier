## 2024-05-20 - Notebook Plot Accessibility & Standards
**Learning:** Default Matplotlib plots in notebooks without explicit markers or legends are difficult for colorblind users to distinguish training vs. validation curves, and lack clarity without axis titles.
**Action:** Always include distinguishable markers (`o-` vs `x--`), clear title, axis labels with units, and explicit legend location (`lower right`) for model accuracy/loss evaluation plots in Jupyter Notebooks.
