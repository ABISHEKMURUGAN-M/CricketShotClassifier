## 2025-05-14 - Accessible Plotting in Notebooks
**Learning:** For colorblind accessibility, line plots should use distinguishable markers and line-styles (e.g., 'o-' vs 'x--') in addition to color.
**Action:** Always use distinguishable markers and line-styles when plotting training/validation curves in Jupyter Notebooks.

## 2025-05-14 - Human-Readable Model Outputs
**Learning:** Displaying raw numeric labels in model predictions or evaluations is poor UX; users must mentally map indices to classes.
**Action:** Use `inverse_transform` on the `LabelEncoder` to provide immediate, human-readable feedback for model predictions.
