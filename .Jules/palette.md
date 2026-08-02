## 2023-11-23 - Accessibility of Notebook Plots
**Learning:** For users who have color vision deficiencies (colorblindness), standard color-coded line plots can be completely uninterpretable. Distinguishing between training and validation accuracy lines solely by color does not meet accessibility guidelines.
**Action:** Always plot with distinct markers (e.g., 'o' vs. 'x'), distinct line styles (e.g., solid '-' vs. dashed '--'), and explicit legend labels and axis titles.

## 2023-11-23 - Inverse Transform of Model Outputs
**Learning:** Model predictions that only print raw class indices (e.g., 0, 1, 2) force the user to look up the LabelEncoder classes mapping manually. This introduces high cognitive load and is a poor UX.
**Action:** Decrypt model predictions using inverse_transform on the fitted label encoder (`le.inverse_transform`) to instantly output highly descriptive, human-readable labels to the user.
