"""
==============================================================
ISC–Rating Correlation Analysis and Visualization 
==============================================================

This script performs two major analyses:
1. Behavioral correlations between emotional regulation ratings and ISC.
2. Visualization of ISC or any source-level data on an MNE brain surface.

Required files:
---------------
1. ratingandISCmeg.csv   → Behavioral and ISC measures for correlation.
2. neu_watch_stc5-rh.stc + neu_watch_stc5-lh.stc → Right/Left hemisphere source estimate (MNE format).
3. heads.csv             → Source-level values to map on the brain surface.
4. MNE fsaverage subject (or your subject) in MNE_DATA folder.

Output:
-------
- Spearman correlation results printed in the console.
- Brain visualizations saved as PNG files in the chosen output folder.
"""
