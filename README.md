## Klasyfikacja użytkowników i botów

### Cel projektu

Celem projektu jest przeprowadzenie klasyfikacji kont użytkowników platformy vk.com w celu odróżnienia kont autentycznych od botów za pomocą metod uczenia maszynowego. 

## Wymagania dotyczące danych

- Zbiór danych musi zawierać:
  - Minimum 10 zmiennych objaśniających (cech)
  - Zarówno zmienne kategoryczne, jak i ciągłe
  - Minimalna liczba obserwacji: 1000
- Źródła danych:
  - Własne zbiory danych
  - Publicznie dostępne repozytoria (np. Kaggle, UCI ML Repository)
  - API z danymi
- Problem musi być jednoznacznie zdefiniowany jako:
  - Klasyfikacja (binarna lub wieloklasowa) lub Regresja
 
## Wymagania techniczne
- Jakość kodu:
  - Czytelność i odpowiednie formatowanie kodu
  - Zgodność ze standardem PEP 8
  - Logiczny podział na sekcje
  - Komentarze wyjaśniające kluczowe fragmenty kodu
  
- Wykorzystane biblioteki (minimalny zakres):
  - NumPy i Pandas - przetwarzanie danych
  - Matplotlib/Seaborn - wizualizacja danych
  - Scikit-learn - budowa modeli i tworzenie pipeline'ów danych
 
## Technologie

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-9cf)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## Struktura projektu

## 1. Wprowadzenie
  - Przedmiot oraz cel i zakres badania
    
## 2. Eksploracja i analiza danych
  - Opis zbioru danych/zmiennych
  - Analiza wartości brakujących i odstających
  - Czyszczenie i kodowanie danych 
  - Analiza statystyczna zmiennych 
    
## 3. Wizualizacja danych
  - Wizualizacja rozkładów danych oraz zależności między cechami a klasą docelową
  - Eksploracyjna analiza danych 
    
## 4. Przetwarzanie danych
  - Podział na zbiór testowy i treningowy 
  - Badanie korelacji zmiennych 
  - Skalowanie 
  - Wybór cech 
    
## 5. Stworzenie modeli
  - Wybór modeli i optymalizacja hiperparametrów
  - Ocena skuteczności modeli, walidacja krzyżowa
    
## 6. Podsumowanie wyników i wnioski
  - Podsumowanie badania i sformułowanie wniosków

## Wyniki 

| Model                 | Accuracy | Precision | Recall | ROC-AUC |
|-----------------------|----------|-----------|--------|---------|
| Las Losowy            |  0.956   |   0.953   | 0.960  |  0.956  |
| Gradient Boosting     |  0.967   |   0.957   | 0.977  |  0.966  |
| Regresja Logistyuczna |  0.955   |   0.950   | 0.962  |  0.955  |


## Zbiór danych znajdziesz [tutaj](http://kaggle.com/datasets/juice0lover/users-vs-bots-classification).
