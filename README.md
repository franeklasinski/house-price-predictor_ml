# Predykcja Cen Nieruchomości - Machine Learning

## Opis Projektu

Kompleksowy projekt analizy i predykcji cen nieruchomości wykorzystujący różne algorytmy uczenia maszynowego. Projekt zawiera pełny pipeline od analizy danych, przez porównanie modeli, aż po interaktywną predykcję cen.

## Cele Projektu

- Analiza danych nieruchomości i identyfikacja czynników wpływających na cenę
- Porównanie skuteczności różnych algorytmów Machine Learning
- Optymalizacja hiperparametrów dla uzyskania najlepszych wyników

## Dataset

Dataset zawiera informacje o **545 nieruchomościach** z następującymi cechami:

### Cechy numeryczne:
- **area** - powierzchnia domu (m²)
- **bedrooms** - liczba sypialni
- **bathrooms** - liczba łazienek
- **stories** - liczba pięter
- **parking** - liczba miejsc parkingowych

### Cechy binarne:
- **mainroad** - dostęp do głównej drogi (yes/no)
- **guestroom** - pokój gościnny (yes/no)
- **basement** - piwnica (yes/no)
- **hotwaterheating** - centralne ogrzewanie (yes/no)
- **airconditioning** - klimatyzacja (yes/no)
- **prefarea** - preferowana lokalizacja (yes/no)

### Cechy kategoryczne:
- **furnishingstatus** - stan umeblowania (furnished/semi-furnished/unfurnished)

### Zmienna docelowa:
- **price** - cena domu

## Technologie

- **Python 3.9+**
- **pandas** - manipulacja danymi
- **numpy** - operacje numeryczne
- **scikit-learn** - modele Machine Learning
- **matplotlib** - wizualizacja danych
- **seaborn** - zaawansowane wykresy

## Modele Machine Learning

Projekt porównuje 5 różnych algorytmów:

1. **Random Forest** (podstawowy)
2. **Random Forest** (optymalizowany)
3. **Gradient Boosting Regressor**
4. **Support Vector Regression (SVR)**
5. **AdaBoost Regressor**

### Optymalizacja hiperparametrów
- **Grid Search** z walidacją krzyżową (5-fold CV)
- Automatyczny wybór najlepszego modelu
- Szczegółowa analiza wyników

## Wizualizacje

Projekt zawiera bogate wizualizacje:

- **Macierz korelacji** między cechami
- **Wykresy rozkładów** cen i cech
- **Analiza ważności cech** (Feature Importance)
- **Porównanie modeli** (RMSE i R²)
- **Analiza błędów** predykcji
- **Wykresy rzeczywiste vs przewidywane** ceny

## Instalacja i Uruchomienie

### 1. Klonowanie repozytorium
```bash
git clone https://github.com/franeklasinski/house-price-predictor_ml.git
cd house-price-predictor
```

### 2. Instalacja zależności
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Uruchomienie
```bash
jupyter notebook house-price-analysis.ipynb
```

## Autor
**Franciszek Lasiński**


