# crossmodel_prediction

**ABSTRACT**
Studying perturbations in the gut ecosystem using animal models of disease continues to provide valuable insights into the role of the microbiome in various physiological and pathological conditions. However, understanding whether these changes are consistent across animal models of different genetic backgrounds, and hence potentially translatable to human populations remains a major unmet challenge in the field. Nonetheless, in relatively limited cases have the same interventions been studied in two animal models in the same laboratory. Moreover, such studies typically examine only one data layer and one-time point. Here, we show the power of utilizing time series microbiome (measured by 16S rRNA amplicon profiling) and metabolome (measured by untargeted LC-MS/MS) data to relate two different mouse models of atherosclerosis: ApoE-/-(n=16) and Ldlr-/-(n=24) that are exposed to intermittent hypoxia and hypercapnia (IHH) longitudinally (for 10 weeks and 6 weeks, respectively) to model chronic obstructive sleep apnea. Using Random Forest classifiers trained on each data layer, we show excellent accuracy values in predicting IHH-exposure within ApoE-/- and Ldlr-/- knockout models, and in cross-applying predictive features found in one animal model to the other.  Some of the key microbes and metabolites that predicted IHH-exposure across animal models included bacterial species from the family Clostridiaceae, muricholic acid (a bile acid) and vaccenic acid (a fatty acid), providing a refined set of biomarkers reproducibly associated with this intervention. The results highlight that time series, multi-omics data can be used to relate different animal models of disease to one another using supervised machine learning techniques, and can provide a pathway towards identifying robust microbiome and metabolome features that underpin translation from animal models to understanding human disease.

**IMPORTANCE** Reproducibility of microbiome research is a major topic of contemporary interest. Although it is often possible to distinguish individuals with specific diseases within a study, the differences are often inconsistent across cohorts, often due to systematic variation in analytical conditions. Here we study the same intervention in two different mouse models of cardiovascular disease (atherosclerosis) by profiling the microbiome and metabolome in stool specimens over time. We demonstrate that shared microbial and metabolic changes are involved in both models with the intervention. We then introduce a pipeline for finding similar results in other studies. This work will help find common features identified across different model systems, which are most likely to apply in humans.
