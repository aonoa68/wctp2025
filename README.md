# GAN-Based Modeling of Emotional Dynamics in Cultural Evolution and Niche Construction

This repository contains the full code and data associated with the paper:

> Onohara, A., & Ouchi, H. (2025).  
> *GAN-Based Modeling of Emotional Dynamics in Cultural Evolution and Niche Construction: An Integrated Empirical Approach.*  
> Presented at the Workshop on Computation: Theory and Practice (WCTP 2025).

📄 [Replication package on Zenodo (DOI: 10.5281/zenodo.16756127)](https://doi.org/10.5281/zenodo.16756127)

---

## 📁 Repository Structure

- `code/`  
  → Jupyter notebook for full analysis:  
  `GAN_Based_Modeling_of_Emotional_Dynamics_in_Cultural_Evolution_and_Niche_Construction_code.ipynb`

- `data/`  
  → Preprocessed CSV files (anonymized). Used for emotion × stage statistical analysis and GAN input.


---

## 🚀 Getting Started (Locally or in Colab)

### Option 1: Run in Google Colab (recommended)

1. Open the notebook in [Colab](https://colab.research.google.com/)
2. Run the first cell to clone the repository and install packages:
   ```python
   !git clone https://github.com/aonoa68/wctp2025
   %cd wctp2025
   !pip install -r requirements.txt
````

### Option 2: Run locally

```bash
conda env create -f environment.yml
conda activate gan-emotion
jupyter lab
```

---

## 🧪 Reproducibility

Running the notebook will regenerate:

* All figures (Fig. 2–6)
* All tables (Table 1–3, Kruskal-Wallis and GAN evaluations)

No GPU is required. All results are saved to `/figs/` and `/results/`.

---

## 🔒 License

* **Code**: [MIT License](LICENSE)
* **Data**: [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
  © 2025 Ayaka Onohara, Hiroki Ouchi

---

## 🔎 Citation

Please cite this repository and the associated Zenodo archive:

```bibtex
@misc{ono2025rep,
  author       = {Ayaka Onohara and Hiroki Ouchi},
  title        = {Replication package for “GAN-Based Modeling of Emotional Dynamics in Cultural Evolution and Niche Construction”},
  howpublished = {\url{https://doi.org/10.5281/zenodo.16756127}},
  year         = 2025
}
```

