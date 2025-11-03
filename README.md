# product-category-predictor
Analiza datelor produselor
# Product Category Predictor

Autor: Cioaric Rodica  


## Descriere
Proiectul clasifică produsele în categorii pe baza titlului lor folosind Machine Learning.  
Model final: Linear SVM cu TF-IDF vectorizare.

## Structura proiectului
- data/products.csv – setul de date
- notebooks/analysis_and_model.ipynb – notebook cu explorare și antrenare
- scripts/train_model.py – script pentru antrenare
- scripts/predict_category.py – script pentru predicții interactive
- models/ – folder cu modelul și vectorizatorul salvate
- requirements.txt – librăriile necesare

## Instrucțiuni de rulare
1. Instalează librăriile:
```bash
pip install -r requirements.txt
i

