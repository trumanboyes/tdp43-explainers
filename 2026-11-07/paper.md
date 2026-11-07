# Paper

**Ten protein panel predicts ALS from plasma with high accuracy**
Woo Jae Kim, Mingee Chung, Seneshaw Asress, Adam N. Trautwig, Eric Dammer, Christina N. Fournier, Nicholas T. Seyfried, Zachary T. McEachin, Jonathan D. Glass, Eleanor V. Thomas (Emory University, Atlanta, GA).
*Nature Communications*, received Feb 4, 2026; accepted Sep 29, 2026; published online October 19, 2026 (article in press). Open access, CC BY-NC-ND 4.0.

- DOI: https://doi.org/10.1038/s41467-026-78766-5
- Article: https://www.nature.com/articles/s41467-026-78766-5
- Emory news release (Nov 5, 2026): https://news.emory.edu/stories/2026/10/breakthrough-emory-study-earlier-als-detection

## One-line note
Single-center (Emory ALS Center) cross-sectional plasma study using NULISAseq CNS + Inflammation panels (323 analytes) in a development cohort of 632 ALS and 160 healthy controls (spouses / non-familial care partners), with an independent validation cohort of 144 ALS and 37 controls. 84 proteins differed (31 up, 53 down; BH-adjusted). XGBoost with 5-fold nested cross-validation and SHAP feature selection, then forward selection, gave a 10-protein "ERACE" panel: NEFL, pTau-181, CALCA, TREM1, FOLR1, VEGFA, NEFH, PTX3, NRGN, LAMP3. Validation cohort: balanced accuracy 98.3%, AUC 0.992 (1 ALS and 1 control misclassified); NEFL alone 89.9% / AUC 0.916; NEFL+NEFH 89.8% / AUC 0.959; the 9 proteins without NEFL 78.8% / AUC 0.892. Age and sex added negligible information. The panel corrected 44/632 ALS (7.0%) and 17/160 controls (10.6%) misclassified by NEFL alone; those corrected ALS cases were more often male (88.6%), upper-extremity onset (65.1%) and had higher ALSFRS-R (mean 38.1 vs 33.4). One "ALS" case called control by the model was later found to have inclusion body myositis (IBM). Freezer storage time shifted many analyte levels but not classification. Caveats: healthy controls only (not ALS mimics or other neurodegenerative diseases), single center, single time point; not yet a clinical test. Summary based on the full article PDF.
