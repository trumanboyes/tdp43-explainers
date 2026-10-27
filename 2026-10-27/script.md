# Script: Can AI find hidden TDP-43 errors, and point to a new biomarker?

*Narrated by ElevenLabs (voice: Carolyn). Plain-English explainer, not medical advice.*

Hi. Tonight's paper is a preprint, posted on bioRxiv on October 9, 2026, so it has not been peer reviewed yet. It comes from Johns Hopkins University, with first author Cristina Martin-Linares and senior author Jonathan Ling. The title is: "Fine-tuning genomic models on rare splicing events identifies a novel biomarker of TDP-43 pathology."

Some background. In almost everyone with ALS, a protein called TDP-43 leaves the cell's nucleus, where it normally works. One of its jobs is editing genetic messages. It keeps out hidden pieces, called cryptic exons. When TDP-43 is lost, those pieces get stitched in, and the message can break or make a strange new protein. Known examples include STMN2 and UNC13A. These cryptic exons matter because they could become tests that show TDP-43 trouble in a living person. But they're hard to find, especially in brain cell types that are difficult to grow in the lab.

What did they do? The team asked whether artificial intelligence could learn to predict cryptic exons from DNA sequence alone. They compared two kinds of models. One is AlphaGenome, a very large general-purpose model of the genome. The other is OpenSpliceAI, a smaller model built only to predict splicing. They trained both on cryptic exons already found in about 270 human genes, then tested them on genes and mouse cryptic exons the models had never seen.

What they found. The specialized model learned well. On the mouse test, its scores went up roughly eight- to ten-fold after training. The big general model, with only a new final layer added, failed completely. Only when the whole model was retrained did it improve, reaching roughly two-thirds to four-fifths of the specialist's score. The trained models also picked up how known ALS risk variants in UNC13A change splicing there. Still, these predictions are far from perfect.

Then the team scanned every human gene with the specialized model. It flagged new cryptic exons in two genes, CLDN11 and ARHGAP23. They checked postmortem brain tissue from people with frontotemporal dementia caused by TDP-43, a condition closely related to ALS. The new pieces showed up in some patient samples, but not in controls. They also tended to appear where TDP-43 problems were seen in oligodendrocytes, the cells that wrap nerve fibers in insulation.

What it means. In the brain, CLDN11 is made almost only by those insulating cells. The cryptic version is predicted to give the protein a brand-new tail. If antibodies can detect that tail, it might someday become a test for TDP-43 trouble in these support cells, much like a cryptic protein from HDGFL2 is being explored as a marker for neurons.

Honest caveats. This is a preprint. The brain tissue came from dementia cases, not ALS, and only some samples showed the signal. The new CLDN11 protein has only been predicted, not yet found. And there is no blood or spinal fluid test yet.

What's next? The obvious next steps are making antibodies to the new protein, then checking whether it shows up in spinal fluid, and in ALS tissue. This is educational only, not medical advice. Talk with your care team about your own situation.

---
Source: Martin-Linares CP, Peethambaran Mallika A, Sandal PS, Martin TW, Morris M, Wong PC, Ling JP. "Fine-tuning genomic models on rare splicing events identifies a novel biomarker of TDP-43 pathology." bioRxiv preprint, Oct 9, 2026. https://doi.org/10.64898/2026.10.07.757366
