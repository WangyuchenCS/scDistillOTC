# 🧬 scDistillOTC: Generative Modeling of Unseen Single-Cell Perturbations

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Official implementation of the paper:  
**“Generative Modeling of Unseen Single-Cell Perturbations via Knowledge Distillation and Optimal Transport”**

---

## 🚀 Overview

**scDistillOTC** is a lightweight generative model designed to predict cellular responses to genetic or pharmacological perturbations at the single-cell level.  
It integrates:

- ✅ **Variational Autoencoder (VAE)** with cycle consistency  
- ✅ **Knowledge Distillation** from pretrained single-cell foundation models  
- ✅ **Optimal Transport (OT)** for unpaired distribution alignment

The model is particularly effective at handling **unseen cell types**, enabling robust perturbation inference across datasets and limited data settings.  
This tool transforms static single-cell atlases into **dynamic resources for genetic therapy development**.

---

## 📂 Usage

A complete example is provided in [`Tutorial.ipynb`](Tutorial.ipynb), which includes:

- 📥 Loading and preprocessing single-cell perturbation datasets  
- 🧠 Initializing and training the `scDistillOTC` model  
- 🔮 Predicting perturbation responses for unseen cell types  
- 📊 Visualizing gene expression recovery and differential expression

---

## 📄 Documentation

Full documentation and API reference will be available upon paper publication.  
In the meantime, please refer to the paper PDF and the tutorial notebook for architecture and training details.

---

## 📈 Performance Highlights

- Outperforms state-of-the-art models (scGen, trVAE, scPRAM, CellOT, etc.) on **unseen and unpaired** perturbation tasks  
- Enables **cross-study prediction**, harmonizing data from different experimental sources  
- Recovers both **global expression profiles** and **top DEGs** with high fidelity  
- Robust under **limited data** (as low as 10%) per sensitivity analysis

---

## 🤝 Contributing

Contributions are welcome!  
If you encounter issues or want to add new features, feel free to:

- 📌 Open an issue  
- 🔧 Submit a pull request

---

## 📚 Citation

If you use **scDistillOTC** in your research, please cite our work:

