# Machine Learning Midterm Assignment

This repository contains the midterm assignment for the Machine Learning course. The project explores supervised classification (Decision Tree, KNN, Gaussian Naive Bayes) and unsupervised clustering (K-Means) on two different datasets.

## Datasets
The datasets used in this project are loaded directly from the `scikit-learn` library:
*   **Breast Cancer Wisconsin (Diagnostic):** `sklearn.datasets.load_breast_cancer`
*   **Wine Classification:** `sklearn.datasets.load_wine`

## Project Structure
*   `breast_cancer.ipynb`: Data exploration, preprocessing, model training, and evaluation for the Breast Cancer dataset.
*   `wine.ipynb`: Data exploration, preprocessing, model training, and evaluation for the Wine dataset.
*   `report.docx`: The final project report containing result summaries, tables, and interpretations
*   `*.csv` files: 6 required CSV files containing model runs and summaries (`classifier_runs.csv`, `classifier_summary.csv`, `classifier_test.csv`, `kmeans_runs.csv`, `kmeans_summary.csv`, `kmeans_test.csv`)
*   `AI_DISCLOSURE.md`: Transparency report on the use of AI tools during the project
*   `requirements.txt`: List of Python packages and versions required to run the notebooks

## Requirements and Installation
This project was developed using **Python 3.13**. To run the notebooks, you need the following packages

*   `pandas==3.1.1`
*   `scikit-learn==1.9.1`
*   `numpy==2.5.4`
*   `matplotlib==3.11.2`
*   `seaborn==0.13.2`

**How to install:**
1. Clone this repository to your local machine.
2. Open your terminal or command prompt.
3. Install the dependencies using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt