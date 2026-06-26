## 2025-05-14 - [Notebook Visualization Standards]
**Learning:** In machine learning notebooks, accuracy and loss plots are often bare. Adding titles, legends, and axis labels significantly improves readability. For accessibility, especially for colorblind users, using distinguishable markers ('o', 'x') and line styles ('-', '--') is a critical UX requirement.
**Action:** Always include comprehensive labels and distinguishable styles in matplotlib plots.

## 2025-05-14 - [Model Output Readability]
**Learning:** Raw model predictions (e.g., [0, 2, 1]) are not user-friendly. Users should not have to refer back to the LabelEncoder to understand results.
**Action:** Use `inverse_transform` to decode numeric labels into human-readable strings before displaying outputs.
