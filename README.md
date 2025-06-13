# 🐑 Eid Al-Adha 2025: Sheep Classification Challenge

Welcome to my submission for the **Kaggle Competition**:  
**"Eid Al-Adha 2025: Sheep Classification Challenge"**  
Hosted by **Dal**, this competition celebrates Eid Al-Adha by encouraging participants to build an AI model to classify 7 Arabian sheep breeds.

## 📌 Objective

Build a machine learning model that can accurately classify images into one of the following 7 sheep breeds:

- **Naeimi**
- **Najdi**
- **Harri**
- **Goat**
- **Sawakni**
- **Roman**
- **Barbari**

---

## 📦 Download Dataset

To download the dataset, make sure you have installed and authenticated the **Kaggle CLI**:

```bash
pip install kaggle
kaggle competitions download -c sheep-classification-challenge-2025
unzip sheep-classification-challenge-2025.zip
```

## 🗂️ Project Structure
```
├── train/                  # Training images
├── test/                   # Test images (optional, depends on Kaggle setup)
├── train_labels.csv        # CSV with image filenames and breed labels
├── model.ipynb             # Notebook with explanations and annotations
├── requirements.txt        # Python dependencies
└── README.md               # This file
```
## 📖 Notebook Overview
The main steps in model_with_markdown.ipynb:
### - Load and Inspect Dataset
Load image-label pairs and preview the label distribution.
### - Balance Dataset
Apply sampling to ensure class balance for better model training.
### - Visualize Sample Images
Display a few images per class to understand visual features.
### - Model Training (CNN models)
### - Evaluation and Submission (Plot accuracy, precision, etc.)

## 🚀 Getting Started
### Requirements
- Python 3.8+
- Jupyter Notebook
- Libraries:
- pandas
- matplotlib
- scikit-learn
- PyTorch (for model training)

### Installation
```bash
pip install -r requirements.txt
```


## 🙏 Acknowledgements
Thanks to Dal and Kaggle for hosting this unique and culturally relevant challenge.
