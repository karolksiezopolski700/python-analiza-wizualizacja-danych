## English

# Analysis of the Impact of Mbappe and Vinicius on Real Madrid’s Results

## Project Description
The goal of this project is a comparative analysis of the impact of Kylian Mbappe and Vinicius Junior
in Real Madrid matches during the 2024/25 and 2025/26 seasons, and an examination of how this impact
changes depending on the strength of the opponent, measured using the ELO rating.

The project covers the full data analysis workflow:
- data acquisition,
- data cleaning and transformation,
- integration of match data with ELO rankings,
- result visualization and interpretation of findings.

## Data Sources
- Match data: football-data.org API  
- Team ELO rankings: ClubElo

## Technologies
- Python
- pandas
- matplotlib
- requests
- Jupyter Notebook

## Scope of Analysis
- analysis of match results against weaker and stronger opponents (ELO > 1800),
- comparison of goal contributions (goals + assists),
- visualization of differences between the players.

## Project Structure
- `01_data_preparation.ipynb` – data acquisition and preprocessing
- `01_data_preparation.html` – data acquisition and preprocessing (HTML version)
- `02_visualisation.ipynb` – analysis and visualization of results
- `02_visualisation.html` – analysis and visualization of results (HTML version)
- `data/` – source files (ELO rankings)
- `matches_elo.csv` – transformed data used for visualization

## Conclusions
The analysis shows that Mbappe has a greater impact on goal scoring than Vinicius in most matches.
However, these differences decrease in games against the strongest opponents, indicating that
a broader context should be considered when comparing the performance of both players.

## Note
Part of the code that retrieves data from the API requires generating a personal API key by creating
an account on football-data.org. The code will not run correctly without prior configuration.

## Polski

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
- `matches_elo.csv` - dane po transformacji używane do wizualizacji

## Wnioski
Analiza pokazuje, że Mbappé ma większy wpływ na zdobywane bramki niż Vinícius w większości meczów,
jednak różnice te zmniejszają się w spotkaniach przeciwko najsilniejszym rywalom,
co wskazuje na konieczność uwzględniania szerszego kontekstu przy porównywaniu wydajności obu zawodników.

## Uwaga
Część kodu pobierająca dane z API wymaga wygenerowania własnego klucza API tworząc konto na football-data.org.
Kod nie zostanie poprawnie wykonany bez wcześniejszej konfiguracji.
