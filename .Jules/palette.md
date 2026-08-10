## 2024-08-10 - Colorblind Plot Accessibility
**Learning:** Using different markers and line styles (like 'o' with '-' and 'x' with '--') makes line plots readable for colorblind users who cannot distinguish red vs green.
**Action:** Always use distinguishable markers and line styles in notebook plots.

## 2024-08-10 - Notebook Plot Usability
**Learning:** Raw distribution histograms in data science notebooks lack context unless explicit titles, labeled axes with units (such as 'Sequence Length (Frames)' and 'Frequency (Count)'), and distinguishable borders or fills are provided to guarantee usability and accessibility.
**Action:** Always decorate pandas series or matplotlib histograms with set_title(), set_xlabel(), and set_ylabel() with clear units, and remove distracting defaults like background grids where unnecessary.
