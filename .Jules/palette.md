## 2026-03-30 - Accessible Matplotlib Line Plots in Notebooks
**Learning:** Model accuracy plots in notebooks often lack accessible visual indicators for training vs. validation series, making them hard to distinguish for colorblind users or when printed in grayscale.
**Action:** Always include distinctive markers (`marker="o"` vs `marker="x"`), line styles (`linestyle="-"` vs `linestyle="--"`), clear axis labels, titles, and explicitly placed legends (`loc="lower right"`) for notebook plots.
