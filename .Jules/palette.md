## 2025-05-18 - Notebook Plot & Prediction UX
**Learning:** Raw numeric predictions from machine learning models in notebooks lack clarity for end-users. Decoding predictions using `inverse_transform` into human-readable class names provides immediate understanding. Additionally, using distinguishable line markers ('o', 'x') alongside line styles in matplotlib charts makes training vs validation metrics accessible to colorblind users.
**Action:** Always decode model outputs to class labels and add visual markers to plot lines in Jupyter notebooks.
