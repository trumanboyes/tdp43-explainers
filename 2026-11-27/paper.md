# Paper

**Neuronal cell-cycle re-entry stratifies clinical trajectories in amyotrophic lateral sclerosis**

Jonathan Plessis-Belair, Roger B. Sher (Department of Neurobiology and Behavior and Center for Nervous System Disorders, Stony Brook University, NY, USA). *Brain*, advance article published online November 11, 2026 (accepted manuscript). Peer reviewed; open access (CC BY-NC 4.0). Funding: NIH (K12GM102778, R01AG079898), WaterWheel Foundation; authors report no competing interests.

- DOI: https://doi.org/10.1093/brain/awag391
- Article: https://academic.oup.com/brain/advance-article/doi/10.1093/brain/awag391/9031944
- Analysis code: https://github.com/jonathanplessis-belair/NeuronalCCR-in-ALS
- Patient data: Answer ALS Data Portal (https://dataportal.answerals.org)
- Note: summary based on the accepted-manuscript full text; supplementary material not read.

## What the study did
- Re-analysed RNA-sequencing from iPSC-derived motor neurons in the Answer ALS cohort: 624 individuals (445 ALS, 161 healthy controls, 10 non-ALS motor neuron disease, 8 asymptomatic gene carriers). UMAP + k-means clustering gave 10 molecular subgroups; linked to ALSFRS-R (n = 290) and survival (n = 227) with mixed-effects models.
- Reproduced cluster signatures by qPCR in motor neurons from five Answer ALS iPSC lines (SOD1 and C9orf72 lines from the cell-cycle-high cluster 7, one sporadic ALS line with high cyclin E, two controls).
- Mechanism: human NGN2-induced spinal motor neurons treated with importazole (10 µM), an importin-β nuclear-import inhibitor; SILAC spatial proteomics, Ki-67/cyclin time courses, DNA-content FACS, EdU and γH2AX staining, washouts, FUDR (blocks DNA synthesis), and CDK4/6 inhibitors palbociclib and abemaciclib (5 nM).

## Key results
- Cluster 7 had strong induction of cyclins D, A and B (CCND1, CCNA2, CCNB1) but not cyclin E (CCNE1), with lower stathmins (incl. STMN2) and syntaxins; it showed the slowest ALSFRS-R decline. Moderate cell-cycle activation was linked to the lowest scores ("biphasic" relationship). Overall survival did not differ between clusters.
- Site of onset was the strongest clinical modifier (bulbar/multiple onset faster); sex and mutation category did not significantly alter progression.
- Importazole blocked nuclear import, caused cytoplasmic phosphorylated TDP-43 aggregates in 30–40% of motor neurons, widespread protein mislocalisation (ALS the top enriched pathway), loss of full-length STMN2 and accumulation of truncated STMN2.
- It triggered a transient wave of cell-cycle activity (Ki-67, cyclins peaking days 1–3); S-phase fraction 26.0% vs 18.6% in controls at day 2, without G2 accumulation (abortive). Washout at day 1 was largely harmless; at day 4 it was not.
- Neurons that incorporated EdU (started DNA replication) were almost all γH2AX-positive (DNA damage). FUDR at day 0 rescued survival (later addition did not help or worsened it).
- Low-dose CDK4/6 inhibition reduced DNA synthesis and partly restored STMN2; both drugs trended protective, but only abemaciclib was statistically significant at day 7 (p = 0.0051; palbociclib p = 0.11).

## Caveats
- Patient findings are correlational and come from stem-cell-derived neurons, not brain or spinal cord tissue; cluster sizes for individual analyses are small.
- Importazole is an acute model and may not reflect the slow nuclear-transport decline in human ALS; all drug experiments were short-term in vitro.
- CDK4/6 inhibitors are cancer drugs that have not been tested in people with ALS.
- Authors call for longitudinal datasets and chronic models across genetic and sporadic ALS.

Educational summary only, not medical advice.
