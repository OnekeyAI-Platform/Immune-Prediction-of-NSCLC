# Immune Prediction of Non-Small Cell Lung Cancer

## Abstract：

**Objective:**
 To develop a predictive model using weakly supervised deep learning to accurately forecast major pathological response (MPR) in patients with resectable non-small cell lung cancer (NSCLC) undergoing neoadjuvant chemoimmunotherapy (NICT) by leveraging whole slide images (WSIs).

**Methods:**
 This retrospective study analyzed pre-treatment WSIs from 186 NSCLC patients using a weakly supervised learning framework. We employed advanced deep learning architectures, including DenseNet121, ResNet50, and Inception V3, to analyze WSIs at both patch and slide levels. The training process incorporated data augmentation and normalization techniques to enhance model robustness. We compared these models with traditional clinical predictors and integrated them with a novel pathomics signature developed through multi-instance learning algorithms that aggregate features from patch-level probability distributions.

**Results:**
 Univariate and multivariable analyses identified histology as a significant prognostic factor for MPR (P < 0.05). DenseNet121 outperformed ResNet50 and Inception V3 in validation (AUC = 0.656) and demonstrated strong generalization in external testing (AUC = 0.611). XGBoost exhibited superior class differentiation and generalization, achieving the highest AUCs of 0.998 in training, 0.818 in validation, and 0.805 in testing. Integrating pathomics features with clinical data into a nomogram improved discriminative accuracy (AUC = 0.819 in validation and 0.820 in testing). Grad-CAM and feature aggregation methods significantly enhanced model interpretability.

[Power by OnekeyAI](http://medai.icu/)