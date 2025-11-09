# Modeling Memory Retention with Ebbinghaus's Forgetting Curve Streamlit Deployment

<div align="center">

<img src="https://img.shields.io/badge/Framework-Streamlit-red?logo=streamlit" />
<img src="https://img.shields.io/badge/Model-XGBoost-blue?logo=xgboost" />
<img src="https://img.shields.io/badge/Explainability-SHAP-yellow?logo=python" />
<img src="https://img.shields.io/badge/License-MIT-green?logo=open-source-initiative" />

</div>

---

## Overview

This project models **human memory retention** using **Ebbinghaus’s Forgetting Curve**, enhanced by **machine learning techniques** for interpretability and behavioral understanding.  
It applies **XGBoost** regression to predict memory retention while integrating behavioral factors such as sleep quality, stress levels, and learning methods.  
The goal is to make Ebbinghaus’s model adaptive and explainable in modern learning contexts.

---

## Live Demo

**Deployed Application:**  
[EbbinghausMind – Streamlit App](https://ebbinghausmind.streamlit.app/)

The Streamlit application allows users to:
- Input behavioral and learning factors.  
- Predict memory retention over time.  
- Visualize SHAP-based model explainability interactively.  

---

## Repository Structure

```bash
.
├── .devcontainer
│   └── devcontainer.json          # Configuration for containerized development
│
├── app.py                         # Streamlit app entry point
│
├── model.pkl                      # Trained XGBoost model for memory retention prediction
│
├── requirements.txt               # Python dependencies for the project
