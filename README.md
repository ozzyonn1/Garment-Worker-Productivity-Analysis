# Produktywność pracowników przemysłu odzieżowego – projekt analizy danych

## Tytuł projektu

Przewidywanie produktywności pracowników na podstawie cech zespołu i środowiska pracy

## Źródło danych

Oryginalny zbiór danych pochodzi z:  
[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees)

## Format projektu

Analiza została przeprowadzona w formie jednego notebooka Jupyter:  
`Eksploracja_Danych.ipynb`

---

## Cel projektu

Celem projektu było stworzenie modeli klasyfikacyjnych przewidujących poziom produktywności pracowników sektora odzieżowego na podstawie danych operacyjnych i zespołowych.  
Projekt został zrealizowany w ramach przedmiotu Eksploracja Danych na Politechnice Lubelskiej w roku 2025.  
Analiza obejmuje pełen proces eksploracji danych: od wstępnego przygotowania zbioru, przez eksplorację zależności i selekcję cech, aż po budowę i ocenę modeli predykcyjnych.

## Zastosowane techniki i narzędzia

- Wstępna analiza i oczyszczenie danych
- Uzupełnianie braków danych (SimpleImputer, imputacja dominującą wartością)
- Standaryzacja danych numerycznych (StandardScaler)
- Kodowanie zmiennych kategorycznych (OneHotEncoder)
- Selekcja cech (SelectKBest z mutual_info_classif)
- Budowa modeli: Logistic Regression, Random Forest, k-NN, SVM, MLP
- Kalibracja hiperparametrów (GridSearchCV)
- Ocena skuteczności modeli: accuracy, precision, recall, F1-score
- Wizualizacje: wykresy korelacji, wykresy ROC i Precision-Recall, macierze pomyłek
- Interpretacja ważności cech (feature_importances_, coef_)

## Najlepszy model

Najlepszy wynik uzyskał model Random Forest, który osiągnął najwyższą wartość F1-score i bardzo dobre zrównoważenie metryk jakości klasyfikacji.  
Model ten może służyć jako narzędzie wspierające zarządzanie produktywnością zespołów w zakładach produkcyjnych.

## Autorzy

- Oleh Zemlianyi  
- Emil Szewczak  
Politechnika Lubelska, 2025

## Licencja

Projekt udostępniony na licencji [Apache License 2.0](LICENSE).

---

*Projekt zgłoszony w ramach zaliczenia przedmiotu Eksploracja Danych 2025.*
