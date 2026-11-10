---
title: "Celesto: Exoplanet Habitability Lab"
excerpt: "Multi-model ML pipeline scoring exoplanet habitability from atmospheric, orbital, and surface features."
collection: portfolio
date: 2025-12-01
---

A multi-model machine learning pipeline that combines atmospheric, orbital, and surface features to score the habitability of exoplanets.

**Stack:** Python, Scikit-Learn, NASA Exoplanet Archive, Streamlit

**Highlights**
- Three specialised models, one per feature group: **Gradient Boosting Regressor**, **Random Forest Classifier**, and **RBF-SVM**, trained on 25+ exoplanetary features.
- Model outputs are combined with a **Logistic Regression** meta-model.
- Sanity-checked qualitatively on known exoplanets: unfavourable cases scored lower and potentially habitable candidates scored higher.
- Interactive **Streamlit** app.

[Code]([URL](https://github.com/angelavarghese/celesto)) · [Live app](URL)
