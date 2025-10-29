# Web Scraping Nieruchomości 

## 🎯 Cel projektu
Celem projektu było pozyskanie i przygotowanie danych dotyczących cen mieszkań w Polsce w celu dalszej analizy lub wykorzystania w modelach do prognozowania wartości nieruchomości.

Dane te mogą wspierać firmy z branży nieruchomości, analityków finansowych i deweloperów w podejmowaniu decyzji inwestycyjnych, analizie trendów cenowych oraz optymalizacji ofert sprzedażowych.

## 📌 Zakres realizacji

- **Web scraping ze serwisu [gratka.pl](https://gratka.pl)**  
  Pobranie ofert nieruchomości z województwa wielkopolskiego
  Zgromadzenie kluczowych informacji: `Tytuł`, `Opis`, `Cena`, `Metraż`.

- **Import danych z serwisu Kaggle**  
  Pobranie gotowego zbioru danych o nieruchomościach w Polsce.  
  Wyodrębnienie analogicznych zmiennych (`Tytuł`, `Opis`, `Cena`, `Metraż`).

- **Integracja danych z serwisu Kaggle**  
  Import gotowego zbioru danych o nieruchomościach w Polsce.
  Ujednolicenie struktury i zmiennych 

- **Czyszczenie i przygotowanie danych**  
Usunięcie duplikatów oraz rekordów z brakującymi wartościami 
Oczyszczenie tekstów z niepotrzebnych znaków specjalnych.
Normalizacja zmiennych numerycznych (`Cena`, `Metraż`).

- **Standaryzacja danych**  
  Normalizacja zmiennych `Cena` oraz `Metraż`.

- **Wykrycie i usuwanie anomalii**  
 Identyfikacja ofert odstających (outlierów) na podstawie wartości minimalnych i maksymalnych.

- **Eksport danych**  
  Zapisanie końcowych, przetworzonych zbiorów do plików .csv gotowych do dalszej analizy.



