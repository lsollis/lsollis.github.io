---
permalink: /scholarly-ability/
title: "Evidence of Scholarly Ability"
author_profile: true
---

*ICS Ph.D. portfolio, category 3.*

The ICS requirement asks for two or more items authored by the student and reviewed by doctoral-level
scholars, and states that two publications satisfy it. I have seven peer-reviewed publications
(five journal articles and two conference papers), four of them as first author; one of these, at
*npj Digital Medicine*, was accepted in October 2026 and is in production. A further first-author
manuscript is in its second round of revision.

Each entry below includes a description of my specific contribution, as required for multi-author work. These descriptions are consistent with the published author-contribution statements in each paper.

## Summary

| # | Venue | Year | Author Position | Venue quality |
|---|---|---|---|---|
| 1 | *npj Digital Medicine* | 2026 (accepted) | **First** | **IF 18.0 (2025 JCR)** |
| 2 | DeCaF, MICCAI 2026 | 2026 | **First, oral** | 58% accept; **top 29% selected for oral** |
| 3 | *Scientific Reports* | 2025 | **First** | IF 4.9 (2025 JCR) |
| 4 | IWBI 2026 proceedings | 2026 | **First** | 18th edition; peer-reviewed proceedings |
| 5 | *npj Digital Medicine* | 2025 | Third | **IF 18.0 (2025 JCR)** |
| 6 | *Scientific Data* | 2026 | Third | IF 7.2 (2025 JCR) |
| 7 | *JMIR Formative Research* | 2026 | Third | IF 2.4 (5-yr 2.8) |

All items except #1 are indexed in Web of Science and Scopus; the four journal articles among them are
also in MEDLINE/PubMed. Item 1 was accepted on October 26, 2026 and is in production; its DOI is pending.

In addition, a first-author scoping review at *PLOS Digital Health* (Q1, reported IF ~8.5) passed
initial peer review with a major-revision decision and is in its second round of revision.

## First-author publications, peer-reviewed

### 1. Artificial intelligence across the skin cancer screening pathway: an umbrella review

**Sollis LJ**, Bunnell A, Cho E, Willingham ML Jr, Cruz-Mattos G, Arii A, Lum C, Cassel K, Shepherd JA.
*npj Digital Medicine*. **Accepted October 26, 2026; in production. DOI pending.** **First author.**

Synthesizes 46 systematic reviews appraised with ROBIS and AMSTAR 2. Finds that over 70% of datasets
came from majority light-skinned populations, that ROBIS flagged high risk of bias in 31 of 46 reviews,
and that no review applied an implementation science framework.

The accepted manuscript is not posted here while it is in production; the link below is the public
preprint of the original submission, posted before peer review; it does not reflect revisions.

[Preprint](https://doi.org/10.21203/rs.3.rs-9069373/v1)

**Evidence of venue quality:** *npj Digital Medicine* (Springer Nature) has a 2025 impact factor of
**18.0** (Journal Citation Reports), the leading journal in digital medicine. Indexed in MEDLINE/PubMed,
Web of Science, and Scopus.

### 2. Personalized federated learning for equitable breast cancer detection in underrepresented Pacific Islander populations

**Sollis LJ**, Young PM, Bunnell A, Quon B, Hernandez BY, Wolfgruber TK, Shepherd JA.
*7th MICCAI Workshop on Distributed, Collaborative and Federated Learning (DeCaF 2026)*,
Strasbourg, France. **First author. Oral presentation.**

Adapted GMIC, a multiple-instance classifier for mammographic cancer detection, for federated
fine-tuning with NVIDIA FLARE, and evaluated shared-global (FedAvg, FedProx) against personalized
(FedBN, Ditto) strategies across a three-site federation including a diverse Pacific Island cohort.
FedAvg, FedProx, and FedBN improved the largest site but left smaller sites at or below pretrained
performance; Ditto improved the worst-performing site and was the most equitable strategy. This work
is directly preliminary to my dissertation work on federated adaptation.

[PDF](/files/decaf-2026-sollis.pdf) · [Supplement](/files/decaf-2026-sollis-supp.pdf)

**My contribution:** I conceived and led this study, adapted GMIC for federated fine-tuning under
NVIDIA FLARE, built the three-site federation and its preprocessing pipeline, implemented and ran all
shared-global and personalized strategies including the module-wise Ditto variant, analyzed the
results, and wrote the manuscript.

**Evidence of venue quality:** DeCaF 2026 received 24 submissions and accepted 14 (58%). Of the 14
accepted papers, 7 were selected for oral presentation, placing this paper in the top 29% of
submissions. DeCaF is the established venue for distributed and federated learning in medical imaging,
now in its 7th edition as a MICCAI satellite event, and proceedings are published by Springer.

### 3. Compact subsets of autism screening items predict clinical diagnoses with a machine learning analysis of the QCHAT-10

**Sollis LJ**, Wall DP, Washington PY. *Scientific Reports*. 2025;15:39091. **First author.**

Trained models on New Zealand and Saudi Arabian QCHAT-10 cohorts and tested transfer to clinically
diagnosed Polish cases. Recursive feature elimination converged on four-item models sharing three
features (eye contact, gaze following, and pretend play), reaching AUROC 85-87% on clinical
diagnoses, demonstrating partial transfer from assessment-score prediction to clinical diagnosis.

[Published article](https://doi.org/10.1038/s41598-025-26131-9) · [PDF](/files/scientific-reports-2025-sollis.pdf)

**My contribution:** I conceived the study, curated the three national datasets, designed the
methodology including the recursive feature elimination and threshold-tuning approach, carried out all
experiments, and wrote the original draft. (Published statement credits me with conceptualization, data
curation, methodology, carrying out experiments, and writing the original draft.)

**Evidence of venue quality:** *Scientific Reports* (Nature Portfolio) has a 2025 impact factor of 4.9
(Journal Citation Reports) and is among the most-cited journals in the world. Indexed in MEDLINE/PubMed,
Web of Science, and Scopus.

### 4. Do deep embedding-derived imaging phenotypes reveal breast cancer risk heterogeneity beyond scalar risk stratification?

**Sollis LJ**, Shvetsov Y, Quon B, Wolfgruber TK, Bunnell A, Hernandez BY, Shepherd JA.
In: Sechopoulos I, ed. *Proceedings of the 18th International Workshop on Breast Imaging (IWBI 2026)*,
Thessaloniki, Greece. Zenodo; 2026:423-432. **First author.**

Tested whether unsupervised clustering of Mirai embeddings identifies stable, clinically meaningful
phenotypes beyond the scalar risk score, across 26,573 HIPIMR women and 79,317 screening examinations.
Clustering was highly stable (ARI > 0.98), but the recovered groups tracked predicted risk rather than
distinct clinical phenotypes. I report this negative result directly: it constrains what Mirai's learned
representation can be said to encode, and it is part of what motivates my dissertation work on where
mammographic models lose information.

[Proceedings](https://zenodo.org/records/22122618)

**My contribution:** I co-conceived and led the study, constructed the HIPIMR analytic cohort, designed and
ran the clustering and stability analyses, and wrote the manuscript.

**Evidence of venue quality:** The International Workshop on Breast Imaging is the principal
international meeting dedicated to breast imaging, now in its 18th edition, with peer-reviewed
proceedings. The 2026 scientific program comprised 36 proffered oral presentations and 80 posters.
IWBI does not publish an acceptance rate.

## Co-author publications, peer-reviewed

### 5. Quantifying device type and handedness biases in a remote Parkinson's disease AI-powered assessment

Tumpa ZN, Shahriar Zawad MR, **Sollis L**, Parab S, Chen IY, Washington P.
*npj Digital Medicine*. 2025;8(1):550.

[Published article](https://doi.org/10.1038/s41746-025-01934-2)

**My contribution:** I implemented the web-based assessment platform with two co-authors and co-led
participant recruitment for the study. The device-type and handedness biases characterized here are
properties of the collection instrument I helped build, which is what makes this finding
methodologically relevant to my dissertation's treatment of acquisition shift.

**Evidence of venue quality:** *npj Digital Medicine* (Springer Nature) has a 2025 impact factor of
**18.0** (Journal Citation Reports), making it the leading journal in digital medicine. Indexed in
MEDLINE/PubMed, Web of Science, and Scopus.

### 6. RobustPDx: a structured web-based Parkinson's assessment dataset and benchmark for AI robustness to device type and handedness

Tumpa ZN, Shahriar Zawad MR, **Sollis L**, Parab S, Azizian P, Honarmand M, Kargarandehkordi A,
Tarrit K, Abbasi-Asl R, Bove R, Wall DP, Washington P. *Scientific Data*. 2026. Published online August 18, 2026.

A public dataset and robustness benchmark for device-type and handedness effects in remote
Parkinson's assessment: an acquisition-shift problem structurally parallel to the scanner and
protocol heterogeneity my dissertation studies in mammography.

[DOI](https://doi.org/10.1038/s41597-026-08118-x)

**My contribution:** I implemented the web-based assessment platform with two co-authors and co-led
participant recruitment for the study that produced the released dataset. I reviewed and approved the
final manuscript. (Published statement: "M.R.S.Z., L.S., and S.P. implemented the assessment website.
... L.S. ... led recruitment activities.")

**Evidence of venue quality:** *Scientific Data* (Nature Portfolio) has a 2025 impact factor of 7.2
(Journal Citation Reports). It publishes peer-reviewed data descriptors held to explicit reusability and
documentation standards. Indexed in MEDLINE/PubMed, Web of Science, and Scopus.

### 7. Remote assessment of Parkinson disease using deep learning on structured mouse-trace data from suspected cases

Shahriar Zawad MR, Tumpa ZN, **Sollis L**, Parab S, Washington P.
*JMIR Formative Research*. 2026;10:e81368.

[Published article](https://doi.org/10.2196/81368)

**My contribution:** I contributed to study conceptualization and data curation, and helped develop the
web-based assessment platform used to collect the mouse-trace data analyzed here. (Published statement
lists me under Conceptualization, Data curation, and Web development.)

**Evidence of venue quality:** *JMIR Formative Research* has a 2025 impact factor of 2.4 (5-year 2.8).
Indexed in MEDLINE/PubMed, PubMed Central, Web of Science, and Scopus.

## Manuscript in revision

### Machine learning for Parkinson's disease diagnosis using digital technologies: a scoping review

**Sollis LJ**, Jaiswal A, Lim K, Raza F, Kim D, Banerjee A, Zhou AM, Brown E, Bove R, Abbasi-Asl R,
Washington P. *PLOS Digital Health*: **passed initial peer review with a major-revision decision; second
round of revision in progress (since October 27, 2026).** **First author.**

PRISMA-ScR scoping review of machine learning for Parkinson disease diagnosis and monitoring using
consumer digital technologies in real-world settings.

**Evidence of venue quality:** *PLOS Digital Health* ranks in the first quartile (Q1) of its category,
with a Scimago Journal Rank of 1.789 and a reported 2025 impact factor of approximately **8.5**. PLOS
declines to publish impact factors as a matter of editorial policy, so this figure is drawn from
third-party indexes of Journal Citation Reports rather than from the publisher. Indexed in Web of
Science, Scopus, PubMed, PubMed Central, DOAJ, and Dimensions.
