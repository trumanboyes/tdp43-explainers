# Paper

**Donor Aware Reanalysis of Neuronal Nuclei Supports STMN2 Depletion Associated with Nuclear TDP-43 Loss in FTD and ALS**
Abdullah Chaudhary and Saiqi Yao (Union Hospital, Tongji Medical College, Huazhong University of Science and Technology, Wuhan, China). Corresponding: Abdullah Chaudhary / Saiqi Yao (yaosaiqisky@icloud.com).
*bioRxiv* preprint, posted November 3, 2026. CC BY 4.0.

- DOI: https://doi.org/10.64898/2026.10.27.762172
- PDF: https://www.biorxiv.org/content/10.64898/2026.10.27.762172v1.full.pdf
- HTML: https://www.biorxiv.org/content/10.64898/2026.10.27.762172v1
- Source data: GEO GSE126542 / BioProject PRJNA522295 (Liu et al., Cell Reports 2019)
- Analysis code: https://github.com/abdullahchaudhary360/Tdp43-Neuronal-Nuclei-Reanalysis

## One-line note
Secondary, donor-aware PyDESeq2 reanalysis of public FACS-isolated NeuN+ frontal-cortex neuronal nuclei RNA-seq (GSE126542): 62,754 genes, 12 libraries, 7 donors, 5 complete matched pairs (TDP-43 retained vs lost; source labels “positive”/“negative”). Primary design ~ donor + nuclear_status; contrast loss minus retained; sensitivity models ~ nuclear_status and ~ diagnosis + nuclear_status. Donor-aware model: 3,442 genes FDR < 0.05 (1,865 lower, 1,577 higher in loss nuclei). STMN2 depleted: log2FC −1.813 (95% Wald −2.229 to −1.396), FDR 6.22×10⁻¹⁵, ~71.5% lower expression; lower in all 5 complete pairs; also significant in both sensitivity models. TARDBP lower: log2FC −0.606, FDR 4.98×10⁻⁶. UNC13A whole-gene modestly higher in donor-aware model only (log2FC 0.372, FDR 0.00622; ~29.4% higher) and not significant in sensitivity models (FDR ≈ 0.50); authors stress whole-gene UNC13A cannot infer cryptic-exon inclusion or functional depletion. No splice-junction, PSI, isoform, or protein data; no healthy controls; source cohort FTD/FTD–ALS with C9orf72 background; two eligible sorted libraries absent from supplied matrix for undocumented reasons; FASTQ pipeline not re-executed. Limitations stated by authors include small size, selection ambiguity, gene-level-only measurements, and no external validation. Summary based on the full preprint PDF (CC BY 4.0).
