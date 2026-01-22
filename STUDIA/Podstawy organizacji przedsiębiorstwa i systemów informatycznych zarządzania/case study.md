# Informatyzacja przedsiębiorstwa produkcyjnego PROMEB Sp. z o.o.

**Imię i nazwisko:** Maks Nowacki, Bartosz Krzyżański, Wiktor Michałowski
**Numer albumu:** 344397, 344381, 344391
**Miejscowość, data:** Warszawa, 22.01.2026 r.

---

# I. Rekomendacja dla Zarządu PROMEB Sp. z o.o.

**Dotyczy:** Strategii wdrożenia zintegrowanego systemu klasy MRP/ERP

### 1. Jakość (funkcjonalność) produktu finałowego
Rekomendowany system ERP musi być rozwiązaniem hybrydowym, obsługującym specyfikę produkcji w PROMEB.
* **Obsługa BOM i Receptur:** System musi łączyć produkcję dyskretną (montaż płyt MDF/HDF - BOM) z procesową (zużycie klejów, farb, lakierów - Receptury). Jest to krytyczne, ponieważ obecne arkusze kalkulacyjne nie pozwalają na precyzyjne rozliczanie "niedookreślonych" receptur chemicznych.
* **Zarządzanie materiałami specyficznymi:** Niezbędna jest funkcjonalność obsługi wymiarów i atrybutów dla arkuszy oklein naturalnych (fornir), co wyeliminuje błędy w ewidencji magazynowej.
* **Integracja:** System musi spiąć "wyspy informacyjne": finanse, kadry, magazyn i produkcję w jedną bazę danych, zapewniając dostęp do informacji w czasie rzeczywistym.

### 2. Koszt oprogramowania
Inwestycję należy traktować w kategoriach ROI (zwrotu z inwestycji), a nie tylko kosztu.
* Rekomenduje się wybór systemu w modelu, który pozwoli na elastyczne skalowanie (np. subskrypcja lub leasing licencji), co nie obciąży jednorazowo kapitału obrotowego firmy.
* Koszt musi obejmować nie tylko licenzje, ale przede wszystkim analizę przedwdrożeniową i szkolenia dla personelu, który dotychczas pracował na przestarzałych narzędziach.

### 3. Serwis, aktualizacja funkcjonalna i techniczna
Ze względu na 100% polskiego kapitału i działanie w polskim otoczeniu prawnym:
* Wymagany jest dostawca krajowy lub globalny z silnym polskim oddziałem, gwarantujący zgodność z przepisami (JPK, KSeF, RODO).
* Obecne oprogramowanie DOS nie posiada wsparcia – nowy system musi posiadać gwarancję SLA (Service Level Agreement) na min. 99% dostępności.

### 4. Prace adaptacyjne i rozwojowe
System pudełkowy nie pokryje w 100% potrzeb PROMEB.
* Konieczne są prace programistyczne (customizacja) w obszarze konfiguratora produktu (meble na indywidualne zamówienie) oraz integracji z nowymi liniami produkcyjnymi.
* System musi być otwarty (API) na przyszłe wdrożenia, np. system B2B dla kontrahentów.

### 5. Podsumowanie
Wdrożenie systemu ERP to konieczność, by utrzymać tempo rozwoju PROMEB. Pozwoli to na przejście z zarządzania intuicyjnego na zarządzanie oparte na danych, precyzyjne ofertowanie (dzięki dokładnym kosztom produkcji) oraz zabezpieczenie ciągłości działania firmy, która obecnie jest zagrożona przez archaiczne technologie.

---

## II. Analiza porównawcza systemów ERP - PRODUKCJA

Do analizy wybrano trzy systemy popularne na polskim rynku, zdolne obsłużyć specyfikę PROMEB.
  
| Lp. | Kryterium                      | System A: Comarch ERP XL        | System B: Streamsoft Prestiż | System C: Symfonia ERP     |
| :-- | :----------------------------- | :------------------------------ | :--------------------------- | :------------------------- |
| 1   | **Producent**                  | Comarch S.A. (Polska)           | Streamsoft (Polska)          | Symfonia (Polska)          |
| 2   | **Profil Produkcji**           | Dyskretna i Procesowa (Hybryda) | Silny nacisk na Dyskretną    | Głównie Dyskretna          |
| 3   | **Obsługa BOM**                | Zaawansowana, wielopoziomowa    | Zaawansowana, import z CAD   | Standardowa                |
| 4   | **Obsługa Receptur**           | Dedykowany moduł "Receptury"    | Obsługa w ramach technologii | Podstawowa                 |
| 5   | **Rozliczanie chemii (kleje)** | Bardzo dobre (zamienniki)       | Precyzyjne rozliczanie       | Wymaga konfiguracji        |
| 6   | **Konfigurator Produktu**      | Tak (wbudowany)                 | Tak                          | Moduł dodatkowy            |
| 7   | **Planowanie (MRP)**           | Zaawansowane                    | Zaawansowane (met. APICS)    | Podstawowe                 |
| 8   | **Harmonogramowanie**          | Wykresy Gantta, Drag&Drop       | Panel produkcyjny            | Harmonogram zleceń         |
| 9   | **Magazyn (WMS)**              | Zintegrowany (Comarch WMS)      | Zintegrowany                 | Mobilny Magazyn            |
| 10  | **Kadry i Płace**              | Pełna integracja                | Pełna integracja             | Bardzo silny moduł rynkowy |
| 11  | **Finanse (FK)**               | Zintegrowane, wysoka klasa      | Zintegrowane                 | Lider rynku księgowego     |
| 12  | **Baza danych**                | MS SQL Server                   | MS SQL Server                | MS SQL Server              |
| 13  | **Skalowalność**               | Duża (średnie i duże firmy)     | Duża (dedykowany produkcji)  | Średnia (MŚP)              |
| 14  | **Interfejs**                  | Nowoczesny (Wstążka)            | Okienkowy/Panelowy           | Klasyczny/Webowy           |
| 15  | **Mobilność**                  | Aplikacje na kolektory/tablety  | Panel Mistrza na tablety     | Mobilny Kierownik          |
| 16  | **Raportowanie (BI)**          | Wbudowane Business Intelligence | Moduły analityczne           | Raporty własne             |
| 17  | **Model zakupu**               | Licencja / Subskrypcja / Chmura | Licencja / Chmura            | Subskrypcja                |
| 18  | **Popularność w meblarstwie**  | Bardzo wysoka                   | Wysoka                       | Średnia                    |
| 19  | **Koszt wdrożenia**            | Średni / Wysoki                 | Średni                       | Średni                     |
| 20  | **Wsparcie techniczne**        | Szeroka sieć partnerów          | Producent + Partnerzy        | Szeroka sieć partnerów     |

---
## III. Wnioski dotyczące zasadności wyboru


Na podstawie przeprowadzonej analizy oraz specyfiki działalności PROMEB Sp. z o.o. zalecany jest wybór systemu **Comarch ERP XL**.

**Uzasadnienie:**
Głównym argumentem przemawiającym za tym systemem jest jego wyjątkowa w tej klasie zdolność do **hybrydyzacji produkcji dyskretnej i procesowej**. Firma PROMEB, która zajmuje się produkcją mebli (produkcja dyskretna – płyty, okucia), wykorzystuje również materiały w procesach chemicznych (produkcja procesowa – kleje, lakiery, bejce), gdzie normy zużycia opierają się na recepturach, a nie na stałych ilościach. Comarch ERP XL posiada dedykowane mechanizmy do obsługi obu tych obszarów jednocześnie.

Ponadto system posiada wbudowany **konfigurator produktów**, który ma kluczowe znaczenie dla produkcji mebli „na indywidualne zamówienia klientów”. Pozwala to na automatyczne generowanie technologii i cen w oparciu o parametry podane przez klienta, zastępując ręczne, pracochłonne obliczenia.

Wybór polskiego producenta (Comarch) zapewnia również bezpieczeństwo w zakresie szybkiego dostosowania się do zmian w polskim prawie podatkowym i prawie pracy, co jest ważne dla firmy z 100% kapitałem krajowym, która chce uniknąć ryzyka prawnego i podatkowego związanego z przestarzałym oprogramowaniem DOS.
