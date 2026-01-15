# Analiza wpływu Mbappe i Viniciusa na wyniki Realu Madryt

## Opis projektu
Celem projektu jest analiza porównawcza wpływu Kyliana Mbappe i Viniciusa Juniora
w meczach Realu Madryt w sezonach 2024/25 i 2025/26 oraz sprawdzenie,
jak zmienia się on w zależności od siły przeciwnika mierzonej rankingiem ELO.

Projekt obejmuje pełny proces analizy danych:
- pobranie danych,
- czyszczenie i transformację danych,
- integrację danych meczowych z rankingiem ELO,
- wizualizację wyników oraz interpretację wniosków.

## Źródła danych
- Dane meczowe: API football-data.org  
- Rankingi ELO drużyn: ClubElo

## Technologie
- Python
- pandas
- matplotlib
- requests
- Jupyter Notebook

## Zakres analizy
- analiza wyników w meczach przeciwko słabszym i silnym rywalom (ELO > 1800),
- porównanie liczby udziałów bramkowych (gole + asysty),
- wizualizacja różnic pomiędzy zawodnikami.

## Struktura projektu
- `01_data_preparation.ipynb` – pobranie i przygotowanie danych
- `01_data_preparation.html` – pobranie i przygotowanie danych w formacie html
- `02_visualisation.ipynb` – analiza i wizualizacja wyników
- `02_visualisation.html` – analiza i wizualizacja wyników w formacie html
- `data/` – pliki źródłowe (ranking ELO)
- matches_elo.csv - dane po transformacji używane do wizualizacji

## Wnioski
Analiza pokazuje, że Mbappé ma większy wpływ na zdobywane bramki niż Vinícius w większości meczów,
jednak różnice te zmniejszają się w spotkaniach przeciwko najsilniejszym rywalom,
co wskazuje na konieczność uwzględniania szerszego kontekstu przy porównywaniu wydajności obu zawodników.

## Uwaga
Część kodu pobierająca dane z API wymaga wygenerowania własnego klucza API tworząc konto na football-data.org.
Kod nie zostanie poprawnie wykonany bez wcześniejszej konfiguracji.
