# Poradnik dla nowych mentorów (wersja robocza)

Poniższy dokument ma na celu ułatwienie nowym mentorom przeprowadzenie pierwszego szkolenia S2. Jest ściągawką, wyciągiem z istniejących dokumentów i opisem struktury szkolenia, wymieniając wszystkie niezbędne tematy, które powinny zostać poruszone. Dokument nie jest za to wyczerpującym kompendium wiedzy szczegółowo opisującym każde z zagadnień.


## Struktura szkolenia

### Szkolenie S1
1. Szkolenie prowadzone jest zgodnie z Regulaminem Szkoły Kontrolerów PLVACC §9
   - Szkolenie teoretyczne DEL/GND i wewnętrzny test teoretyczny PLVACC w core - omówienie procedur i zagadnień wymaganych na pozycjach Delivery/Ground
   - Sesja pokazowa Vatsim - instruktor prowadzi ruch, prezentacja obsługi oprogramowania
   - Szkolenie Sweatbox, weryfikacja umiejętności ucznia, rekomendacja do awansu S1. mentor zgłasza do ACCPL2 lub upoważnionej przez niego osoby prośbę o wygenerowanie testu teoretycznego VATEUD S1, oraz informuje o zdaniu testu przez ucznia. ACCPL2 wnioskuje wtedy o przyznanie uczniowi ratingu S1. Przed rozpoczęciem sesji online na Vatsim w ramach szkolenia S2 należy się upewnić, że ranga S1 została przyznana, nie wystarcza tu sam fakt zdanego testu.teoretycznego.
2. Scenariusze sweatbox można pobrać z Core: ATC Resources->Other->Sweatbox scenarios
3. Mentor może wedle uznania wprowadzić do szkolenia elementy TWR

### Szkolenie S2
1. Szkolenie prowadzone jest zgodnie z Regulaminem Szkoły Kontrolerów PLVACC §10
   - szkolenie teoretyczne TWR i wewnętrzny test teoretyczny PLVACC w core - omówienie procedur i zagadnień wymaganych na pozycji Tower
   - sesja pokazowa w sieci Vatsim, gdzie mentor prowadzi ruch a uczeń obserwuje
   - sesje nadzorowane przez mentora, gdzie uczeń prowadzi ruch pod nadzorem mentora. Sesje online z mentorem prowadzone są do momentu zapoznania się ucznia z oprogramowaniem, specyfiką pozycji i obsługą najczęściej występujących typów operacji. Zwykle do wymaganego poziomu dochodzi się po ok. 4 sesjach. W zależności od postępów ucznia można ten okres wydłużyć lub skrócić
   - Sesje SOLO - wymagane zdanie przez ucznia testu teoretycznego VATEUD S2, generowanego przez ACCPL2. W tym wypadku, inaczej niż przy S1, po zdaniu testu nie wnioskuje się jeszcze o przyznaniu ratingu S2. Zdanie testu wymagane jest jednak do samodzielnego logowania się do sieci przez ucznia. SOLO endorsement przyznawany jest na 30 dni po kliknięciu przez mentora w panelu szkolenia praktycznego przycisku "SOLO RDY". W trakcie sesji solo mentor pozostaje do dyspozycji ucznia w kwestii pytań powstałych podczas samodzielnych sesji. Zaleca się kontrolowanie postępów ucznia (jako OBS lub dodatkowe sesje nadzorowane)
   - sesja sprawdzająca - prowadzona przez mentora po zakończeniu etapu SOLO. Nie jest tu konieczne czekanie do zakończenia trwania sesji SOLO, można przeprowadzić sesję sprawdzającą przed upływem 30 dni SOLO. W przypadku stwierdzenia przez mentora gotowości ucznia do egzaminu należy fakt ten potwierdzić klikając "EXAM READY" w panelu mentora w core.
   - egzamin CPT - po zgłoszeniu przez mentora gotowości ucznia do podejścia do egzaminu 
2. W szczególnych wypadkach można wnioskować o przyznanie kolejnych 30 dni sesji solo. Należy wtedy mieć na uwadze, że nie wydłuża to maksymalnego czasu szkolenia S2, który wynosi 90 dni od rozpoczęcia szkolenia
7. Egzamin CPT powinien odbyć się maksymalnie 60 dni po rozpoczęciu przez ucznia sesji SOLO
8. Analogicznie jak w przypadku awansu na S1 należy przypomnieć uczniowi, że po zdanym egzaminie CPT samodzielne logowanie do sieci na pozycji TWR może nastąpić dopiero po przyznaniu przez VATEUD rangi S2, samo zdanie egzaminu CPT nie wystarczy. Awans przyznawany jest zwykle w przeciągu 1-3 dni.

## Elementy szkolenia
1. Omówienie przebiegu szkolenia
   - S1 - teoria/sesja pokazowa/szkolenie sweatbox zakończone egzaminem S1
   - S2 - teoria/sesja pokazowa/sesje nadzorowane
   - sesje SOLO - egzamin S2 VATEUD, warunki (minimum 10 godzin w 30 dni), remarksy w controller info
   - OTS z mentorem
   - egzamin
2. Wstęp 'legislacyjny'
   - core vacc
     - panel szkolenia     
     - self checkin
   - źródła wiedzy
     - PLVACC policy
     - PLVACC INOP, regulamin szkolenia
     - dokumenty rzeczywiste - AIP, 4444, 9432
3. Omówienie Euroscope
    - podłączenie do Sweatboxa, scenariusze szkoleniowe
    - klient audio - AfV/TrackAudio
    - podłączenie do sieci
      - mentor/uczeń
      - atis, token, manualne nadpisywanie parametrów
      - hoppie code - cpdlc/dcl
      - częstotliwość
      - aktywne pasy
    - praca na listach, statusy, edycja planu, przydzielanie squawk
    - general settings
    - display settings
    - GRPlugin - okno APP, dep timer, TTT, wind rose, filtrowanie widoczności etykiet
4. Lotnisko EPKK
   - przestrzeń odpowiedzialności - powtórka z zasad obowiązujących w klasie D
   - dostępne rodzaje podejść - ILS/LOC/VOR/RNP/Vis - minima i ograniczenia
   - współpraca z sąsiadującymi służbami
   - restrykcje kołowania ze względu na rozpiętość skrzydeł a/c
   - odladzanie
   - operacje wojskowe
   - śmigłowce
5. Obsługa IFR
   - walidacja planu lotu - trasa, poziom przelotowy
   - EOBT/CTOT, co oznaczają, obowiązki, FLS, VDGS
   - przydzielanie kodów transpondera, mode S
   - przejście do lotu VFR
6. Obsługa VFR
   - minima VMC, operacje VFR SPEC
   - punkty VFRowe, oczekiwanie, wlot/opuszczenie CTR
   - obsługa ruchu w kręgu
   - operacje HEMS - priorytety, lądowiska, lądowanie w terenie przygodnym
   - niestandardowe requesty pilotów - base training, imitacje, strefy szkolne
   - przejście do lotu IFR
7. Koordynacja
    - rozpoczęcie/zakończenie sesji (atis, aktywne pasy, .break)
    - go around
    - niestandardowe odloty
    - odpowiedzialność za separacje na prostej i kontrola prędkości podchodzących a/c
    - koordynacja na VACS/Discord
8. Inne
   - omówienie pozostałych lotnisk dostępnych w ramach ratingu S2
   - omówienie roster recency
   - aktualizacja sektora
   - ścieżka rozwoju w PLVACC - kolejne ratingi, grupy robocze, zostanie mentorem


## dodatkowe informacje

1. Sesje treningowe z mentorem i egzaminy CPT/OTS mają pierwszeństwo nad normalnymi bookingami
1. Event Poland Sunday odbywający się w Krakowie jest eventem szkoleniowym. Oznacza to, że pierwszeństwo do pozycji TWR i APP mają uczniowie. Warunkiem jest obecność mentora, uczeń nie może uczestniczyć w evencie samodzielnie w ramach sesji SOLO
1. Mentor zapisuje logi sesji nadzorowanych i przechowuje je do zakończenia szkolenia
2. Uczeń zapisuje logi sesji solo i przechowuje je do zakończenia szkolenia
3. Egzaminator zapisuje logi sesji CPT/OTS i przechowuje je co najmniej 7 dni (czas na potencjalne odwołanie od wyniku egzaminu)

## Źródła
1. [Regulamin Szkoły Kontrolerów w PLVACC](https://cv.plvacc.pl/storage/app/public/documents/QRFFPVS3QBrTnBPmHjPEAAtqrpuUTw5Zggdgdca6.pdf)
2. [VATEUD Division Trainig Policy (DTP)](https://core.vateud.net/division/policies)
3. [VATEUD CPT Guidelines](https://core.vateud.net/division/policies)