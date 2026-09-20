## 2025-05-18 - Accessible Chart Styling and Human-Readable Predictions in Notebooks
**Learning:** Raw matplotlib line plots without distinct markers/styles are inaccessible to colorblind users, and numeric array predictions reduce model output clarity.
**Action:** Always combine distinguishable markers/styles (`o-` vs `x--`), clear titles, labeled axes, and legends in notebook plots, and decode numeric predictions with `inverse_transform` into human-readable class names.
