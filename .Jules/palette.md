# Palette UX Journal

## 2025-05-18 - Colorblind Accessible Notebook Plots
**Learning:** Default line plots in Jupyter notebooks often rely solely on color to differentiate datasets (e.g. training vs validation accuracy), rendering them inaccessible to colorblind users. Moreover, missing titles and axis labels force users to guess plot context.
**Action:** When adding or updating Matplotlib/Seaborn plots in notebooks, always include explicit titles, axis labels, distinguishable markers (`o`, `x`), line styles (`-`, `--`), and legends with optimal placement.
