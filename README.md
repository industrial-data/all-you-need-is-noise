# All You Need Is Noise

This repository contains the material supporting the publication:

**All You Need Is Noise — from feature selection to explainable industrial AI**  
Published in *Digital Chemical Engineering*  
https://www.sciencedirect.com/science/article/pii/S2772508126000037

---

## Overview

This work introduces a simple and model-agnostic idea: **use synthetic noise features as a reference to assess what is truly informative in a dataset**.

By augmenting the input space with random (noise) variables, the model itself can reveal which real features carry signal and which behave no better than noise. This provides a practical baseline for:

- Feature selection  
- Model interpretation  
- Regularization and robustness checks  
- Industrial AI workflows where explainability is required  

The approach is intentionally simple and broadly applicable.

---

## Repository contents

- **JMP files**  
  Experiments, workflows, and analyses used in the paper.

- **Datasets (XLSX)**  
  Data exported from JMP for inspection and reuse.

- **Python reproduction notebooks**  
  Python notebooks are being added to reproduce the paper results and figures alongside the original JMP workflows.

---

## Python notebook index

Use the links below to open the Python reproduction notebook for the result you want to inspect.

### Supervised learning

- [Figures 1 to 3: tree models](01_supervised/results/python/trees/figures_1_to_3_tree_models.ipynb)
- [Figure 4: tree regularization](01_supervised/results/python/trees/figure_4_tree_regularization.ipynb)
- [Figure 5: neural networks](01_supervised/results/python/neural_networks/figure_5_neural_networks.ipynb)

### Unsupervised learning

- [Figures 6 to 8: density dataset PCA reproduction](02_unsupervised/01_density_dataset/results/python/figures_6_7_8_density_pca_reproduction.ipynb)
- [Figures 9 to 11: Tennessee Eastman Process PCA reproduction](02_unsupervised/02_TEP/results/python/figures_9_10_11_tep_pca_reproduction.ipynb)
- [Figure 12: Tennessee Eastman Process bootstrap forest](02_unsupervised/02_TEP/results/python/figure_12_tep_bootstrap_forest.ipynb)

### Design of experiments

- [Figures 13 and 14: pyDOE and LightGBM reproduction](03_DoE/python/reproduce_figures_13_14_pydoe_lightgbm.ipynb)

### Active learning

- [Figures 15 to 17: active learning reproduction](04_Act_Learning/python/reproduce_figures_15_16_17_active_learning.ipynb)
- [Active learning experiment notebook](04_Act_Learning/python/2025-05-28-normal-noisy-test_functions_standarized_paper_parallel_length.ipynb)

---

## Getting started

- Open the JMP files to explore the analyses  
- Use the XLSX datasets for quick access to the data  
- Run the Python notebooks above to reproduce the corresponding paper figures  

---

## Citation

If you use this work, please cite:

All You Need Is Noise — from feature selection to explainable industrial AI  
Digital Chemical Engineering  
https://www.sciencedirect.com/science/article/pii/S2772508126000037

---

## License

This repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

See [LICENSE.md](LICENSE.md) for full terms.

---

## Disclaimer

This repository is provided for research and educational purposes only.  
Use of the materials is at your own risk.

The authors and their affiliated institutions make no warranties and are not liable for any damages arising from its use.

This disclaimer applies to all files and materials in this repository. See [LICENSE.md](LICENSE.md).
