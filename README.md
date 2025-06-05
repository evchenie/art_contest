# Artists Can Design Memory, and AI Can Predict It

This repository contains the full dataset and analysis code accompanying the preprint:

**"Artists Can Design Memory, and AI Can Predict It"**  
available at  https://osf.io/preprints/psyarxiv/3g5az_v1 

---

## 📁 `data/`

This folder includes all data used in the analyses reported in the manuscript. It contains:

- Artwork-level metadata (e.g., artist background, contest category, size, medium)
- Low-level image features (e.g., hue, saturation, luminance, edge density)
- Spatial layout data from the physical gallery exhibition
- Behavioral results from online (Exp. 1) and in-gallery (Exp. 2) memory experiments
- Subjective human ratings (Exp. 3) across 21 attributes (e.g., beauty, complexity, emotional valence, reconstructability)
- AI-based memorability scores from ResMem

The data file is stored in `.csv` format and is analysis-ready.

**High-resolution versions of the contest artworks are available via the project’s OSF repository (https://osf.io/y3mdr/files/osfstorage), under the folder `Artworks`.**
- **86 artworks** were accepted and used in the experiments and analyses described in the paper.
- **4 additional artworks** are included for completeness but were not used in any analysis (e.g., due to disqualification or artist withdrawal).
  
**Note:** Each image filename in the `Artworks` folder is indexed to match the `Image_Num` column in this data CSV (`All_Predictors`), allowing direct correspondence between artwork images and their associated metadata and Behavioral results.

---

## 📁 `notebooks/`

This folder contains all Python notebooks used for:

- Running statistical analyses (e.g., regressions, clustering, PCA)
- Generating all figures included in the main text 

Each notebook is documented for reproducibility and follows the structure of the manuscript.

---

## 📄 Citation

If you use this dataset or codebase in your own work, please cite our accompanying paper.
