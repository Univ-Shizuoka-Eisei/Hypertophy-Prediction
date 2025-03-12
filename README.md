[README_20250312.md](https://github.com/user-attachments/files/19201571/README_20250312.md)

# Machine Learning on Toxicogenomic Data Reveals a Strong Association between the Induction of Drug-Metabolizing Enzymes and Centrilobular Hepatocyte Hypertrophy in Rats 

This repository contains analysis code for the research paper on **Machine Learning on Toxicogenomic Data Reveals a Strong Association between the Induction of Drug-Metabolizing En-zymes and Centrilobular Hepatocyte Hypertrophy in Rats** in rat repeated-dose toxicity tests using machine learning models such as LightGBM and SHAP analysis.

## Repository Structure
The repository includes the following Jupyter Notebooks:

1. **comparsion_models.ipynb**  
   - Compares the performance of multiple machine learning models (e.g., LightGBM, XGBoost, Random Forest, etc.) on the same dataset.
   - Evaluates the models using appropriate performance metrics.

2. **train_lightGBM_and_SHAP_analysis.ipynb**  
   - Trains a LightGBM model to predict centrilobular hepatocellular hypertrophy.
   - Uses SHAP (SHapley Additive exPlanations) to interpret the model's output and analyze feature importance.

## How to Use (Google Colab)
1. Open Google Colab:  
   [https://colab.research.google.com](https://colab.research.google.com)

2. Upload the notebook files to Colab or mount your Google Drive:

   - To mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Run the notebook cells step-by-step.

## Results
- The performance of different models is evaluated based on metrics such as accuracy, F1 score, and ROC-AUC.
- SHAP analysis provides insights into the most influential features contributing to the model's predictions.

## Dataset
- The dataset used for training and evaluation is not included in this repository.  
- If you need access to the dataset, please contact the author directly.

```
@article{your_citation_key,
  author = {Author Name},
  title = {Title of the Paper},
  journal = {Journal Name},
  year = {2025},
  volume = {XX},
  pages = {XX-XX},
  doi = {10.xxxx/xxxxx}
}
```
