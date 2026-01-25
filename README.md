# 📊 Projekt: Analiza Finansów Osobistych (Pandas)

## 🎯 Cel projektu
Celem projektu jest analiza danych dotyczących **wydatków użytkowników** z wykorzystaniem biblioteki **Pandas**.
Projekt skupia się na:
- eksploracji danych finansowych,
- identyfikacji głównych źródeł kosztów,
- analizie wydatków cyklicznych (recurring),
- wykrywaniu koncentracji wydatków,
- formułowaniu praktycznych wniosków biznesowych.

Projekt **nie wykorzystuje Machine Learningu** – jego celem jest pokazanie solidnych umiejętności analizy danych w Pandas.

---

## 🛠️ Technologie
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📁 Struktura projektu
- analysis.ipynb    # Główny notebook
- README.md         # Opis projektu
- requirements.txt  # Lista bibliotek

## 📊 Opis danych
Dataset zawiera **1200 transakcji** oraz **7 kolumn**, m.in.:
- `user_id` – identyfikator użytkownika
- `transaction_id` – identyfikator transakcji
- `amount` – kwota transakcji
- `category` – kategoria wydatku (food, rent, transport itd.)
- `payment_method` – metoda płatności
- `month` – miesiąc
- `is_recurring` – flaga wydatku cyklicznego (0/1)

Dane są kompletne – brak wartości brakujących.

---

## 🧩 ETAPY ANALIZY

### ETAP 1 – Exploratory Data Analysis (EDA)
- Podstawowy opis danych (`info`, `describe`)
- Rozkład kategorii wydatków
- Analiza metod płatności
- Analiza wydatków w czasie
- Porównanie wydatków cyklicznych i jednorazowych

---

### ETAP 2 – Agregacje per użytkownik
- Liczba transakcji per użytkownik
- Suma, średnia i maksymalna kwota wydatków
- TOP 10 użytkowników wg łącznych wydatków
- Analiza koncentracji wydatków
- Klasyfikacja użytkowników (low / medium / high spender)

---

### ETAP 3 – Analiza zaawansowana
- Analiza TOP 10% najdroższych transakcji
- Kategorie o najwyższej medianie wydatków
- Udział wydatków cyklicznych w całkowitych kosztach
- Identyfikacja użytkowników o wysokiej koncentracji wydatków
- Wyszukiwanie obszarów potencjalnych oszczędności

---

### ETAP 4 – Wnioski biznesowe
- Największy wpływ na budżet mają kategorie: **food**, **rent**, **transport**
- TOP 10% transakcji generuje znaczną część całkowitych wydatków
- Wydatki cykliczne stanowią istotny koszt długoterminowy
- Użytkownicy z wysoką koncentracją wydatków w jednej kategorii są najbardziej podatni na optymalizację kosztów
---

### ETAP 5 – Rekomendacje finansowe
- Kontrola i redukcja wydatków cyklicznych
- Skupienie się na największych pojedynczych transakcjach
- Optymalizacja kluczowych kategorii kosztów
- Priorytetowa analiza użytkowników o wysokiej koncentracji wydatków

---

## ✅ Wnioski końcowe
Projekt pokazuje, że:
- Pandas pozwala na pełną analizę finansową bez użycia ML
- Kluczowe informacje biznesowe można uzyskać poprzez odpowiednie agregacje i filtrowanie danych
- Nawet prosta analiza może prowadzić do realnych rekomendacji oszczędnościowych

---

## 🚀 Autor: Wiktor Naczk
Projekt wykonany jako część nauki **Data Science / Analizy Danych**
z naciskiem na **praktyczne wykorzystanie Pandas**.