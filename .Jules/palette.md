# Palette's Journal - Critical Learnings

## 2024-03-20 - Distinguishable markers and line-styles for accessibility in notebook plots
**Learning:** Standard model accuracy and loss plots in Jupyter Notebooks are often difficult for colorblind users to read if they rely solely on color (e.g., solid blue vs. solid orange lines). Using unique markers and different line styles (e.g., solid line with circles vs. dashed line with crosses) makes the plots highly readable and accessible.
**Action:** Always apply distinguishable markers and line-styles (e.g., marker='o' and linestyle='-' vs marker='x' and linestyle='--') to differentiate training and validation lines, and ensure proper legends and titles are present.
