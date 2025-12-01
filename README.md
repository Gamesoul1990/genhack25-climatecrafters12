# ClimateCrafters #12 – GenHack'25

**Systematic bias in urban satellite products: urban origin and operational correction**
The data of hackathon are available on this drive : https://drive.google.com/drive/folders/1_uMrrq63e0iYCFj8A6ehN58641sJZ2x1?usp=drive_link

## Key Results
- ERA5-Land underestimates the real UHI by **0.68 °C** on average (max 1.23 °C in Nice)
- Error **directly linked to urbanization level** (r = -0.64, p < 10⁻¹⁰)
- Random Forest model + NDVI + 5 variables : **MAE = 0.43 °C** ; **-37% error** vs ERA5-Land
- Full explainability with SHAP

## Repository Content
- `week4_team12.ipynb` : complete and commented notebook
- `figures/` : all key visualizations
- `data/` : structure (data too large for GitHub, but everything is reproducible)


Thanks to organizers and jury!
