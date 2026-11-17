# Universal Mast Cell Biomarker

# Boolean implication analysis identifies MRGPRX2 as a lineage-restricted mast cell biomarker

## Summary
This project develops a computational framework to identify transcriptomic biomarkers of mast cell abundance and specificity across diverse human datasets. Using Boolean implication analysis, lineage-informed filtering, and multi-cohort benchmarking, the goal is to move beyond conventional mast cell-associated markers and define biomarkers that remain reliable across tissues, diseases, and experimental settings.

Key Findings:
- Built a two-step discovery pipeline combining Boolean implication analysis with mast cell-versus-basophil prioritization.
- Identified a compact six-gene mast cell signature.
- Observed that some signature genes still show background expression in basophils, but MRGPRX2 remained the most consistently specific.
- Concluded that MRGPRX2 is the strongest candidate for a universal mast cell biomarker.
- Identified that MRGPRX2 could play a key prognostic role in breast cancer cases.

## Requirements
- Python
  - [ScanPy](https://scanpy.readthedocs.io/en/stable/) (v1.9.1)
  - [Matplotlib](https://matplotlib.org/) (v3.5.3)
  - [BoNE](https://github.com/sahoo00/BoNE) (Boolean Network Explorer)


## Citation
```
@article{pltBioMarker2026,
  title  = {Boolean implication analysis identifies MRGPRX2 as a lineage-restricted mast-cell biomarker},
  author = {H M Zabir Haque, Prisha Kaushik, and Debashis Sahoo},
  note   = {Manuscript under review}
}
```
