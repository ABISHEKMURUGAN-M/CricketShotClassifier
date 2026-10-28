## 2025-10-28 - Colorblind Accessibility in Notebook Plots
**Learning:** Matplotlib plots in Jupyter Notebooks without line markers or custom styling rely solely on color to differentiate training vs. validation series, making them inaccessible to colorblind users. Adding explicit markers (e.g. 'o-' vs 'x--'), titles, labeled axes, and legends ensures plot clarity for all users.
**Action:** When updating or creating plot cells in notebooks, always include accessible line markers, labeled axes with units/names, titles, and legends.
