## Web Scraping Nieruchomości – Projekt Analizy Cen Mieszkań

#🎯 Cel projektu:
Celem projektu jest przygotowanie danych do analizy lub budowy modeli uczenia maszynowego w kontekście cen mieszkań w Polsce.
#Zakres realizacji:
-Web scraping ze strony gratka.pl:
  Pobranie danych ofert nieruchomości z województwa wielkopolskiego.
  Zmienne do pobrania: Tytuł, Opis, Cena, Metraż.
-Import danych z serwisu Kaggle:
  Pobranie gotowego zbioru danych o nieruchomościach w Polsce.
  Wyodrębnienie analogicznych zmiennych (Tytuł, Opis, Cena, Metraż).
-Integracja danych:
  Dodanie obu źródeł do osobnych DataFrame.
-Czyszczenie danych:
  Usunięcie duplikatów (ofert o identycznym Tytule, Opisie i Cenie).
  Usunięcie rekordów z brakującymi danymi w kolumnach Cena i Metraż.
  Oczyszczenie kolumn Tytuł i Opis z niepotrzebnych znaków specjalnych.
-Standaryzacja danych:
  Normalizacja zmiennych Cena oraz Metraż.
-Wykrycie i usunięcie podejrzanych ofert:
  Usunięcie outlierów na podstawie wartości minimalnych i maksymalnych dla Cena i Metraż.
-Eksport danych:
  Zapisanie przetworzonych zbiorów do osobnych plików .csv.
