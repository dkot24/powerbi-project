Retail Store Dashboard - Power BI
📊 Opis projektu:

Interaktywny dashboard sprzedażowy stworzony w Power BI, wizualizujący dane z bazy PostgreSQL. Projekt przedstawia kompleksową analizę sprzedaży sklepu odzieżowego z perspektywą produktową, geograficzną i czasową.

🎯 Cel projektu
Stworzenie end-to-end rozwiązania Business Intelligence - od projektowania bazy danych w PostgreSQL, przez modelowanie danych, po interaktywną wizualizację w Power BI umożliwiającą self-service analytics.

🛠️ Technologie

Database: PostgreSQL
Visualization Tool: Microsoft Power BI Desktop
Data Modeling: DAX (Data Analysis Expressions)
Connection: DirectQuery/Import mode

📈 Funkcjonalności dashboardu

Kluczowe wizualizacje:

Quantity sold by category - wykres pierścieniowy pokazujący strukturę sprzedaży według 5 kategorii

Sales by product - ranking 15 produktów z wizualizacją wolumenu sprzedaży

Total sales by category - szczegółowe porównanie 9 kategorii produktowych

Sales per month - analiza trendu sprzedażowego (styczeń 2025 - styczeń 2026)

Geographic filters - 12 interaktywnych przycisków dla różnych rynków (Brazil, France, Germany, Italy, Japan, Poland, Russia, Spain, Sweden, UK, USA, Egypt)

Domestic sales - dedykowany widok dla rynku krajowego

Total Sales KPI - centralny wskaźnik: 6,98 tys. sztuk


Interaktywność:

✅ Cross-filtering między wszystkimi wizualizacjami
✅ Multi-select w filtrach geograficznych
✅ Dynamic tooltips z dodatkowymi informacjami
✅ Drill-down capabilities dla szczegółowej analizy
✅ Automatyczna aktualizacja wszystkich metryk przy filtrowaniu

📊 Insights biznesowe

T-shirt Basic jest bestsellerem (13 sztuk, 19% sprzedaży)
Kategoria T-Shirts stanowi 32,69% całkowitej sprzedaży
Wyraźna sezonowość letnia - szczyt w lipcu (~10,5 jednostek)
Działalność na 12 rynkach międzynarodowych (4 kontynenty)
Portfolio: 15 aktywnych produktów w 9 kategoriach

🗄️ Struktura danych
Dashboard wykorzystuje dane z bazy PostgreSQL (struktura dostępna w tym repozytorium).
Główne tabele:

Products
Categories
Sales
Countries
Calendar/Date dimension

💡 Co można analizować?

Produkty - które produkty i kategorie sprzedają się najlepiej
Geografia - porównanie wydajności różnych rynków
Czas - identyfikacja sezonowości i trendów
Cross-analysis - np. "jakie produkty sprzedają się najlepiej w Polsce w sezonie letnim?"

<img width="1274" height="716" alt="image" src="https://github.com/user-attachments/assets/ee0e41c1-9655-4459-9895-d6091aea8016" />


