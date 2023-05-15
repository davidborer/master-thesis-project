# Master thesis project 
Concordance of genetic information to increase confidence in biomarkers

The code in `analysis.ipynb` contains all analysis and data wrangling for this project. 


Project title: 
### Enhanced Confidence for HER2 Status Predictions in Breast Cancer using Different Genomic Profiles

Abstract: 

Decisions in precision oncology are driven by extensive testing for many
biomarkers. In breast cancer, HER2 is a well established biomarker that is
traditionally tested for by immunohistochemistry (IHC). More recently, next-
generation sequencing (NGS) has become widely used in cancer diagnostics.
However, integrating the different data modalities from NGS such as the total
copy number, allele-specific copy numbers and gene expression into current
clinical practice is a difficult task. Here, we investigated the HER2 status con-
cordance between different NGS data modalities with IHC in a breast cancer
cohort (n = 687) and applied the learnings to a immuno-oncology (IO) cohort
(n = 44). An accuracy of 96.07% was obtained by predicting every sample with
an ERBB2 total copy number higher or equal to 7 as positive. Integrating the
gene expression as well lead to an accuracy of 96.36%. Logistic regression
(LR) and random forest (RF) with the allele-specific copy numbers or all data
modalities did result in very similar accuracies, though not improving the
simple thresholding approach. The thresholding approach was also minimally
successful in the immuno-oncology cohort, where predicting samples with
2 or more CD274 total gene copies as responders lead to a 70% accuracy.
However, the IO cohort was extremely limited in size. Our results confirmed
the very high concordance between ERBB2 amplification in breast cancer and
the HER2 status by IHC. While we were not confident enough to recommend
this integrative approach as a replacement for the IHC test, we recommend it
as a complimentary tool.
