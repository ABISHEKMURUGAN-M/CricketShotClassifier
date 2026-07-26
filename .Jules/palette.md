# Palette's Journal

## 2026-07-25 - Distinguishable Markers and Line-Styles in Model Accuracy Plots
**Learning:** For accessibility and colorblind safety, notebook plots shouldn't rely solely on color to differentiate training and validation curves. Using legends, titles, and distinguishable markers/line-styles (like 'o' with '-' for training and 'x' with '--' for validation) makes plots much more accessible.
**Action:** Always make sure that multiple curves in visual plots utilize different markers and line-styles, accompanied by clear legends and titles.

## 2026-07-26 - Clear Legend and Labeled Axes in Notebook Distribution Histograms
**Learning:** Raw histograms in notebooks are uninformative and inaccessible without explicit descriptions. Describing histograms with custom colors, distinct bin edges, a descriptive title, and fully labeled X and Y axes dramatically improves plot readability and user understanding.
**Action:** Always wrap standard pandas/matplotlib `.hist()` calls with ax methods to set an informative title, clear X-axis labels (with units), and Y-axis labels.
