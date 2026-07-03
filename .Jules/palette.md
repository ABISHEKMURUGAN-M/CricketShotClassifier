## 2025-05-14 - Accessible Notebook Plots and Human-Readable Labels
**Learning:** Model accuracy plots are often inaccessible to colorblind users if they only rely on color. Additionally, integer labels in predictions (e.g., [0, 2, 1]) are not intuitive for users.
**Action:** Always use distinguishable markers ('o', 'x') and line-styles ('-', '--') in notebook plots. Ensure model outputs are decoded into human-readable labels using `inverse_transform` to improve interpretability.
