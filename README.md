# Stellar Light Curve Analysis — SRG/eROSITA

This Jupyter Notebook **LCCP.ipynb** (LightCurveClusteringPeriod) demonstrates automated analysis of stellar light curves from the **SRG/eROSITA** telescope.
See **aPer_poster594x841_.pdf** as a preliminary result of the project, presented at the *“Physics of Stars in the Multiwavelength Era”* conference (2025).

## Project Goal
Determine stellar rotation periods and improve data analysis by minimizing manual review.

## Workflow
1. **Data Preparation**  
   Loading and cleaning light curves from the SRG/eROSITA archive.

2. **Clustering**  
   Grouping similar curves for each star based on shape and statistical features.

3. **Weighted Aggregation**  
   Computing averaged curves, weighted by quality and number of points.

4. **Visualization & Quality Check**  
   Plotting individual and aggregated curves to verify results.

## Outcome
- Robust averaged light curves for ~1000 stars.  
- Automatic rejection of noisy observations improves period estimation.  
- Presented at the *“Physics of Stars in the Multiwavelength Era”* conference (2025), see **aPer_poster594x841_.pdf** for details.
- A paper based on this work is currently in preparation.

## Demo
Graphs from the notebook illustrate clustering and aggregated light curves.  
<img width="1589" height="592" alt="image" src="https://github.com/user-attachments/assets/5cd6259e-e575-4f09-befe-dc9d872f41cc" />
<img width="1586" height="592" alt="image" src="https://github.com/user-attachments/assets/58f2fa8e-4bc8-46d9-9fe3-039bcf811b59" />

Result averaged LightCurve after procedure of weighting
<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/d6c9eee5-08bb-4454-b7af-5d6509e48427" />
