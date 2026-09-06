# Mosquito Species Classification for Disease Prevention — Bangladeshi Dataset Study

> Team poster presentation based on CNN benchmarking (ResNet50, EfficientNetV2-S, VGG16) on AMID V1 balanced subset (2,000 images, 4 classes).

**Original Research Repository:** [AzimPial/Mosquito-Species-Classification-for-Disease-Prevention](https://github.com/AzimPial/Mosquito-Species-Classification-for-Disease-Prevention)  
**Fork maintained by:** [naimasultana553-sys](https://github.com/naimasultana553-sys) for academic poster presentation — Southeast University, CSE.

### Team
- Azim Pial (2023200000601)
- **Naima Sultana (2023200000636)**
- Wahid Imtiaz Arnob (2023200000616)
- Md. Shahadat Hossan (2023200000599)  
Supervisor: Mahdin Mahboob, Assistant Professor, CSE, Southeast University

### Dataset
AMID V1 Balanced Subset — 2,000 images, 500 per class:
- Aedes albopictus
- Culex pipiens  
- Aedes aegypti
- Culex quinquefasciatus  
Source: [AMID V1 on Kaggle](https://www.kaggle.com/datasets/tonmoy406/aedes-mosquito-image-dataset-version-1-0amid-v1)

### Models & Results (Fine-Tuned)
| Model | FT Accuracy | FT F1 | AUC |
|-------|-------------|-------|-----|
| **EfficientNetV2-S** | **92.00%** | **91.93%** | 0.9932 |
| VGG16 | 83.33% | 82.97% | 0.9620 |
| ResNet50 | 77.67% | 76.53% | 0.9601 |

### Poster
- `poster.html` → print-ready A0 poster (841×1189mm)
- `poster_A0.pdf` / `poster_A0.png` / `poster_A0.svg` — exported versions
- `build_poster.py`, `poster_to_svg.py` — generate poster
- `generate_figures.py` — reproduce figures in `assets/` & `figures/`

```bash
python generate_figures.py
python build_poster.py
python poster_to_svg.py
```

### Figures
Training/validation curves, pipeline flowchart, accuracy & time comparisons in `assets/` and `figures/`

### Reports & Notebooks
- `EfficientNetV2_S.ipynb`, `ResNet50.ipynb`
- `EfficientNetV2S_Aedes_Mosquito_Classification_Report.pdf`
- `ResNet50_Aedes_Mosquito_Classification_Report.pdf`

### Citation & Attribution
This repo is a **fork with attribution** for educational poster presentation. Original work by AzimPial. Please cite original repo and AMID V1 dataset. All mosquito images and figures retained from original with credit.

### License
Follow original repository license. For academic use.
