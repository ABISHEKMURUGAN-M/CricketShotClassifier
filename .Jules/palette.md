# Palette's Journal - Critical UX Learnings

## 2025-05-14 - Accessible Plotting in Notebooks
**Learning:** Default line plots are often inaccessible to colorblind users. Using distinguishable markers and different line styles ensures that data series can be identified without relying solely on color.
**Action:** Always include 'o' markers with solid lines and 'x' markers with dashed lines for training/validation plots.

## 2025-05-14 - Human-Readable Model Outputs
**Learning:** Raw model predictions (integers) require users to mentally map indices to labels, increasing cognitive load.
**Action:** Use 'inverse_transform' to decode model outputs into human-readable labels before displaying them to the user.
