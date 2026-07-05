# Palette's Journal

## 2025-05-14 - Distinguishable Markers and Line-styles in Notebook Plots
**Learning:** For users with colorblindness, relying solely on color to distinguish lines in plots is insufficient. Using different markers (e.g., 'o', 'x') and line-styles (e.g., '-', '--') ensures that data series remain distinguishable even in grayscale or for colorblind users.
**Action:** Always use unique markers and line-styles in conjunction with colors for multi-series plots in notebooks.

## 2025-05-14 - Legend Placement for Clarity
**Learning:** In accuracy plots where values often start low and trend upwards, the 'lower right' position for the legend is often the most suitable to avoid overlapping with data points.
**Action:** Default to 'lower right' for legends in training history plots unless data distribution suggests otherwise.
