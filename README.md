# Analiza danych kredytowych

## Opis projektu
Projekt polega na eksploracyjnej analizie danych kredytowych z pliku `credit_koniec_v2.xlsx` w celu zbadania rozkładu zmiennych kategorycznych (np. status konta, cel kredytu). Stworzono sześć wykresów słupkowych w Seaborn, które umożliwiły identyfikację wzorców w danych, wspierających dalsze analizy predykcyjne.

## Technologie
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Git

## Struktura repozytorium
- `data/`: Zawiera próbkę danych (`credit_sample.xlsx`). Pełny zbiór danych dostępny na [Github](#https://github.com/Zypeks/analiza_kredytowa/blob/main/credit_koniec_v2%20(1).xlsx) (jeśli dotyczy).
- `notebooks/`: Notatnik Jupyter z kodem analizy (`Credit_Analysis.ipynb`).
- `requirements.txt`: Lista zależności.

## Jak uruchomić projekt
1. Sklonuj repozytorium: `git clone https://github.com/TwojaNazwaUzytkownika/Credit-Data-Analysis-2023.git`
2. Zainstaluj zależności: `pip install -r requirements.txt`
3. Otwórz notatnik w Jupyter: `jupyter notebook notebooks/Credit_Analysis.ipynb`

## Wyniki
Wizualizacje ujawniły kluczowe wzorce, takie jak dominujący status konta klientów czy najczęstsze cele kredytów, co może wspierać decyzje kredytowe.
