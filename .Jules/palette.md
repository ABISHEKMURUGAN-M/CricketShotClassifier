## 2025-05-18 - Colorblind-Accessible Plot Formatting in Notebooks
**Learning:** Default Matplotlib plots in notebooks relying solely on line color (e.g., training vs. validation accuracy) lack accessibility for colorblind users and clarity for screen readers/reports when title, axis labels, and legends are missing or incomplete.
**Action:** Always include explicit markers (e.g., 'o-' vs 'x--'), titles, labeled axes, and clear legends (such as `loc='lower right'`) for model evaluation plots in Jupyter Notebooks.
