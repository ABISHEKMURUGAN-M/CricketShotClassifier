# Palette's Journal - Critical Learnings

## 2024-05-20 - Notebook Plot Accessibility
**Learning:** Default Matplotlib plots in Jupyter Notebooks lack readable labels, titles, and distinguishable markers for colorblind users when plotting multiple series (e.g. training vs validation accuracy).
**Action:** Always include title ('Model Accuracy'), x-axis ('Epoch'), y-axis ('Accuracy'), legend ('lower right'), and distinct line styles/markers ('o-' and 'x--') for plot series.
