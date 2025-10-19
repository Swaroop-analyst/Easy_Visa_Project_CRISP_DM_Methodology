# EasyVisa_CRISPDM_Project

**Author:** Swaroop Narayan — MBA (expected Nov 2025); MSc in Analytics (expected Nov 2026)

## Overview
This project follows the CRISP-DM methodology to predict visa approval outcomes using the EasyVisa dataset. The notebook `Easy_Visa_Assignment_updated.ipynb` contains the full analysis, EDA, model building (including Gradient Boosting), and evaluation.

## Structure
```
EasyVisa_CRISPDM_Project/
├── 1_Business_Understanding/
├── 2_Data_Understanding/
│   └── visuals/
├── 3_Data_Preparation/
├── 4_Modeling/
│   └── visuals/
├── 5_Evaluation/
├── 6_Deployment/
├── Easy_Visa_Assignment_updated.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

## Quick start
1. (Optional) Create a virtual environment: `python -m venv venv && source venv/bin/activate` (Linux/Mac) or use the equivalent on Windows.
2. Install requirements: `pip install -r requirements.txt`
3. Open the notebook in JupyterLab / Jupyter Notebook and run cells.
4. Visual assets are under the `2_Data_Understanding/visuals` and `4_Modeling/visuals` folders.

## Key findings
- Gradient Boosting Classifier delivered the best performance with a high **F1-score**, making it a strong candidate for reducing both false positives and false negatives in visa approval predictions.

## How to upload to GitHub (web interface)
1. Go to GitHub and create a new repository (e.g., `EasyVisa_CRISPDM_Project`).
2. Click **Add file** → **Upload files**.
3. Drag-and-drop the contents of the unzipped project folder (not the ZIP file itself).
4. Commit the changes. GitHub will render the README and show the folder structure and images automatically.

