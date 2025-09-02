# NLP Rule-Based Text Classification

This project implements **rule-based and traditional NLP preprocessing techniques** for text classification.  
It cleans raw text, applies tokenization, stopword removal, stemming, and evaluates model performance using multiple metrics.

## 🚀 Features
- Text preprocessing with regex, NLTK, and SpaCy
- Stopword removal and stemming
- Train/test pipeline on provided datasets
- Model evaluation using accuracy, precision, recall, F1 score
- Visualization with Matplotlib

## 📂 Repository Structure
```
data/             # Train and test datasets
notebooks/        # Jupyter notebooks
src/              # Python scripts for preprocessing, training, evaluation
requirements.txt  # Project dependencies
README.md         # Project documentation
```

## ⚙️ Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/nlp-rule-based-text-classification.git
   cd nlp-rule-based-text-classification
   ```

2. Create a virtual environment & install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate   # (Linux/Mac)
   venv\Scripts\activate      # (Windows)
   pip install -r requirements.txt
   ```

3. Download SpaCy model:
   ```bash
   python -m spacy download en_core_web_sm
   ```

## ▶️ Usage
- Run preprocessing & training:
  ```bash
  python src/train.py
  ```

- Evaluate results:
  ```bash
  python src/evaluate.py
  ```

- Alternatively, open the notebook:
  ```bash
  jupyter notebook notebooks/nlp_rule_fin_fsss.ipynb
  ```

## 📊 Example Output
- Cleaned dataset samples
- Classification metrics (Accuracy, Precision, Recall, F1-score)
- Token frequency visualization plots

## 🛠️ Technologies Used
- Python 3.x
- NLTK
- SpaCy
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## 👨‍💻 Author
- [Your Name](https://github.com/<your-username>)
