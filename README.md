# Machine Learning Study of Metabolic Networks vs ChEMBL Data of Antibacterial Compounds

## Project Overview

This project analyzes the relationship between bacterial metabolic networks and antibacterial compounds from the ChEMBL database using machine learning approaches.

## Objectives

1. **Data Collection**: Gather antibacterial compound data from ChEMBL and metabolic network data
2. **Feature Engineering**: Extract molecular descriptors and network-based features
3. **Machine Learning**: Build predictive models for antibacterial activity
4. **Analysis**: Identify patterns linking metabolic targets with effective antibacterial compounds

## Project Structure

```
bio_project_sem4/
│
├── data/                    # Raw and processed datasets
│   ├── chembl_antibacterial.csv
│   ├── metabolic_network.csv
│   └── processed/
│
├── notebooks/               # Jupyter notebooks
│   └── main_analysis.ipynb  # Complete analysis workflow
│
├── src/                     # Source code modules
│   ├── data_collection.py
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── ml_models.py
│
├── results/                 # Output figures and results
│
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Run the main Jupyter notebook:
   ```bash
   jupyter notebook notebooks/main_analysis.ipynb
   ```

2. Or run individual modules:
   ```bash
   python src/data_collection.py
   python src/preprocessing.py
   ```

## Methodology

### Data Sources
- **ChEMBL Database**: Bioactive molecules with antibacterial activity
- **KEGG/BioCyc**: Bacterial metabolic pathway data

### Machine Learning Models
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost
- Neural Networks (optional)

### Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC
- Cross-validation scores
### Results
 

## Author

Semester 4 Bioinformatics Project
Ravala Gnanasri Chowdary - cb.sc.u4aie24064@cb.students.amrita.edu

NagiReddy Bhavesh Reddy - cb.sc.u4aie24034@cb.students.amrita.edu

Pratheep Reddy - cb.sc.u4aie24021@cb.students.amrita.edu

Mamidala Som Praneeth Babu - cb.sc.u4aie24029@cb.students.amrita.edu

## License

Academic Use Only
