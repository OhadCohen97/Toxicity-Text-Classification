# Toxicity Text Classification

## Overview

This project implements a classical machine learning pipeline for detecting toxic comments using manual feature engineering and interpretable models. The solution relies on a blend of custom numeric features and text features to train a robust classifier for toxicity detection, with a strong emphasis on transparency and explainability.

---

## Project Structure

```
.
├── ohad_cohen_solution.ipynb         
├── toxicity_toy_dataset.csv         
├── ActiveFence Take-Home Assignment - Ohad Cohen Report.pdf.pdf  # Project report
├── ActiveFence _ Take‑Home Assignment_ Featu re Engineering for Text Classification.pdf # Assignment brief
```

---

## Dataset

- **Source:** Provided as `toxicity_toy_dataset.csv`
- **Description:** Contains 479 short comments labeled as toxic (`1`) or non-toxic (`0`). Each row represents a comment and its toxicity label.

---

## Features

- **Manual Feature Engineering:** Custom features such as comment length, punctuation count, uppercase ratio, and emoji count.
- **TF-IDF Features:** Includes word and character n-grams for richer text representation.
- **Classical ML Model:** Logistic Regression is used for its interpretability and efficiency with sparse data.
- **Reproducible Workflow:** All code and explanations are included in the notebook.

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

Recommended (create a virtual environment):

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Main dependencies (update as needed):

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- emoji

### 3. Run the notebook

Open and run all cells in the notebook for full code, visualizations, and analysis:

```bash
jupyter notebook ohad_cohen_solution.ipynb
```

---

## Files Description

- `ohad_cohen_solution.ipynb`: Full notebook with code, feature engineering, model training, evaluation, and analysis.
- `toxicity_toy_dataset.csv`: The dataset of labeled comments for training and testing.
- `ActiveFence Take-Home Assignment - Ohad Cohen Report.pdf.pdf`: Project summary and discussion of methodology and results.
- `ActiveFence_Take‑Home Assignment_Feature Engineering for Text Classification.pdf`: Assignment instructions.

---

## Results

- **Model:** Logistic Regression classifier trained on engineered features and TF-IDF representations.
- **Performance:** Achieved 95% accuracy on the test set, with robust results validated by 5-fold cross-validation.
- **Analysis:** Feature importance and error analysis are provided in the notebook and the report.

---

## License

For educational use only.

---


