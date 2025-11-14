---
id: weryfikacja-tresci-przed-publikacja
title: Zalecenia dotyczące stworzenia działającego procesu weryfikacji publikowanych treści pod kątem dostępności cyfrowej
opracowanie: Aleksandra Cybulska
data-zgloszenia: 14 listopada 2025 r.
data-aktualizacji:  20 września 2025 r.
wersja_robocza: true
---

## Cel dokumentu
Celem tego opracowania jest przedstawienie rekomendowanego systemu oraz procedur weryfikacji treści cyfrowych - tekstowych i nietekstowych (grafika, multimedia np.: audio, wideo) - 
przed ich publikacją aby zapewnić ich zgodność z zasadami dostępności cyfrowej. System obejmuje także przypadek korekty treści już opublikowanych (np. publikacje niestekstowe w mediach społecznościowych).

## Zakres
Proces obejmuje wszystkie formaty materiałów publikowanych w kanałach cyfrowych organizacji, w tym:
- **Grafiki** (statyczne, infografiki, banery)
- **Pliki tekstowe** (PDF, DOCX, załączniki)
- **Multimedia** (audio, wideo, podcasty, krótkie formy wideo)

## Podstawy prawne i standardy
- **Web Content Accessibility Guidelines WCAG 2.1** (na poziomie AA)
- **Ustawa o dostępności cyfrowej stron internetowych i aplikacji mobilnych podmiotów publicznych**
- **Inne ustawy, wytyczne, standardy krajowe i branżowe**

## Opis procesu weryfikacji

### 1. Etap przygotowania treści
- Autor treści stosuje zasady dostępności:
  - **Teksty**: prosta struktura, nagłówki, listy, język zrozumiały.
  - **Grafiki**: dodanie tekstów alternatywnych (alt).
  - **Multimedia**: przygotowanie napisów rozszerzonych, transkrypcji, audiodeskrypcji (jeśli wymagane).

### 2. Weryfikacja techniczna
- Sprawdzenie:
  - **Grafiki** – czy mają poprawne opisy alternatywne.
  - **Pliki tekstowe** – czy są przygotowane prawidłowo (np. określony język, poprawna struktura nagłówków, obecność tekstów alternatywnych dla osadzonych grafik, zachowany wymagany wskaźnik kontrastu kolorystycznego między tekstem a tłem).
  - **Multimedia** – czy zawierają prawidłowo przygotowane napisy rozszerzone lub transkrypcje czy audiodeskrypcję.

### 3. Narzędzia wspierające
- Automatyczne testery (np. WAVE, axe, Pa11y).
- Walidatory PDF/Word (np. PAC, wbudowane funkcje edytorów treści).
- Kontrola manualna (np. czy alt jest adekwatny do treści prezentowanej na grafice, czy napisy są zsynchronizowane i zapewniają komplet informacji oraz płynność czytania).

### 4. Akceptacja i publikacja
- Publikacja możliwa dopiero po pozytywnej weryfikacji.
- W przypadku braków lub konieczności wprowadzenia poprawek – zwrot do autora z listą obszarów do uzupełnienia lub poprawienia oraz ze wskazaniem narzędzi czy funkcji wbudowanych w edytory, 
z pomocą których można treść prawidłowo przygotować. Skróceniu tego kroku sprzyja możliwość konsultacji ze specjalistą w zakresie dostępności cyfrowej telefonicznej, osobistej.

### 5. Przegląd treści opublikowanych przed kontrolą (media społecznościowe)
UWAGA: specyfiką publikacji w mediach społecznościowych jest dynamika ich powstawania i publikowania (harmonigram działań) oraz - szczególnie w przypadku większych instytucji - ich liczebność. 
Dodatkowo często zdarza się, że funkcje pozwalające zapewniać dostepność w platformach społecznościowych często działają wadliwie i dodanie tekstów alternatywnych lub napisów do filmów 
często nie jest możliwe w czasie publikacji, określonym harmonogramem działań promocyjnych, komunikacyjnych.
- Okresowy (np. cotygodniowy) przegląd publikacji w kanałach społecznościowych instytucji publicznej (obsługiwanych przez dużą grupę osób) pod kątem zgodniości z zasadami dostępności.
- W przypadku braków lub konieczności wprowadzenia poprawek do publikacji – informacja zwrotna do autora publikacji z listą obszarów do uzupełnienia lub poprawienia oraz z ustaleniem terminu wprowadzenia koniecznych zmian.

---

## Role i odpowiedzialności
- **Autor treści** – przygotowanie materiału zgodnie z zasadami dostępności cyfrowej.
- **Osoba weryfikująca** – sprawdzenie zgodności z WCAG i wytycznymi. Konsultacje specjalistyczne.
- **Administrator publikacji** – zatwierdzenie i publikacja.

---

## Rekomendowane dobre praktyki
- Szkolenia dla autorów i weryfikatorów z zakresu tworzenia treści dostępnych cyfrowo.
- Stworzenie podręcznika dla twórców treści cyfrowo dostępnych.
- Stosowanie checklisty dostępności dla każdego typu treści.
- Baza wiedzy z informacjami z zakresu tworzenia treści dostępnych do wykorzystania po szkoleniu.
- Konsultowanie wątpliwości lub trudności autora bezpośrednio ze specjalistą z zakresu tworzenia treści cyfrowo dostępnych (mailowo, telefonicznie, na dyżurach eksperckich).
- Regularne audyty dostępności publikowanych materiałów.

---

## Załączniki
1. **Lista kontrolna dostępności dla grafik**
2. **Lista kontrolna dostępności dla plików tekstowych**
3. **Lista kontrolna dostępności dla multimediów**
   - transkrypcja
   - napisy rozszerzone
   - audiodeskrypcja

---

### **Checklisty dostępności**

#### ✅ Lista kontrolna dla grafik (w tym grafik animowanych, np. *.gif)
- [ ] Każda grafika ma **opis alternatywny (alt)**, który jest zrozumiały i opisuje funkcję lub treść obrazu.
- [ ] Grafiki dekoracyjne oznaczone jako `role="presentation"` lub z pustym alt (`alt=""`).
- [ ] Tekst w grafice nie jest jedynym sposobem przekazania informacji (zapewniona wersja tekstowa).
- [ ] Kontrast kolorów spełnia wymagania WCAG (min. 4.5:1 dla tekstu).
- [ ] Brak migających elementów powodujących ryzyko ataku epilepsji.

---

#### ✅ Lista kontrolna dla plików tekstowych (PDF, DOCX)
- [ ] Dokument ma prawidłową **strukturę nagłówków** (H1, H2, H3), zgodną z hierarchią treści.
- [ ] Tekst jest **czytelny i prosty**, bez zbędnych ozdobników.
- [ ] Plik PDF zawiera **warstwę tekstową** (nie jest obrazem).
- [ ] Opisy alternatywne dla obrazów w dokumencie są dodane.
- [ ] Tabele mają nagłówki kolumn i wierszy.
- [ ] Linki są opisane w sposób zrozumiały (np. „Pobierz raport” zamiast „Kliknij tutaj”).

---

#### ✅ Lista kontrolna dla multimediów (audio, wideo, podcasty) - transkrypcja
- [ ] Transkrypcja przygotowana jest w języku oryginału.
- [ ] Dźwięki opisane są w kolejności takiej, jak na nagraniu
- [ ] Zamieszczenie w nawiasie kwadratowym nazwy mówcy, jeśli w nagraniu jest więcej niż jeden.
- [ ] Umieszczenie adnotacji „W tym pliku dźwiękowym nie ma żadnych wypowiedzi”, jeśli nie występują, np. sama muzyka.
- [ ] Transkrypcja załączona jest w formie pliku lub jako tekst bezpośrednio pod nagraniem.
- [ ] Player multimedialny jest dostępny z klawiatury i dla czytników ekranu.
- [ ] Brak automatycznego odtwarzania lub możliwość jego wyłączenia.

---

#### ✅ Lista kontrolna dla multimediów (audio, wideo, podcasty) - napisy rozszerzone
- [ ] Napisy przygotowane są w języku oryginału.
- [ ] Napisy - najlepiej w oddzielnym pliku .srt - zawierającym kody czasowe, synchronizujące napis z dźwiękiem.
- [ ] Pojedynczy wers napisu zawiera ok. 40 znaków.
- [ ] Pojedyncze wejście składa się z maks. dwóch wersów, wyświetlanych nie krócej niż 3 sekundy.
- [ ] Dźwięki tła lub obrazy, które mają znaczenie dla kontektu wypowiedzi, zapisane są w nawiasie i oddzielnym wersie.
- [ ] Oznaczenie WERSALIKAMI osoby wypowiadającej słowa.
- [ ] Napisy dobrze się czyta, czyli np. nazwy własnych są w jednej linii, w jednym wejściu (ang. caption).
- [ ] Każdy wiersz zakończony jest znakiem przestankowym.
- [ ] Zapewniony jest odpowiedni kontrast między tłem a kolorem napisu.
- [ ] Dostępna jest **transkrypcja** dla materiałów audio i wideo.
- [ ] Player multimedialny jest dostępny z klawiatury i dla czytników ekranu.
- [ ] Brak automatycznego odtwarzania lub możliwość jego wyłączenia.
- [ ] Materiały nie zawierają migających elementów (bezpieczne dla osób z epilepsją).
- UWAGA: Bardziej korzystne jest przygotowanie napisów w postaci "zamkniętej" - oddzielnego pliku np. .srt - jednak, gdy nie ma takiej możliwości, krterium realizuja także napisy "otwarte" - zintegrowane w obrazem wideo. 

---

#### ✅ Lista kontrolna dla multimediów (audio, wideo, podcasty) - audiodeskrypcja
- [ ] Istnieje audiodeskrypcja dla materiałów wideo, jeśli zawierają istotne elementy wizualne ważne dla kontekstu prezentowanej treści.
- [ ] Audiodeskrypcja przygotowana jest w języku oryginału.
- [ ] Audiodeskrypcja czytana jest przez lektora innego niż ten, który wypowiada się w oryginalnej ścieżce dźwiękowej.
- [ ] Audiodeskrypcja nie zakłóca oryginalnego scenariusza filmu.
- [ ] Jeśli treść audiodeskrypcji jest długa i nie mieści się w przerwie między scenami, klatka jest zatrzymana do momentu, gdy wypowiedź z audiodeskrypcji wybrzmi.
- [ ] Wideo zawiera **napisy rozszerzone** zsynchronizowane z dźwiękiem.
- [ ] Dostępna jest **transkrypcja** dla materiałów audio i wideo.
- [ ] Player multimedialny jest dostępny z klawiatury i dla czytników ekranu.
- [ ] Brak automatycznego odtwarzania lub możliwość jego wyłączenia.
- [ ] Materiały nie zawierają migających elementów (bezpieczne dla osób z epilepsją).

---

## Przykładowy workflow (diagram)

```mermaid
flowchart TD
    A[Autor treści] --> B[Przygotowanie materiału zgodnie z zasadami dostępności]
    B --> C[Weryfikacja techniczna przez osobę odpowiedzialną]
    C -->|Braki| D[Zwrot do autora z listą poprawek]
    C -->|OK| E[Akceptacja]
    E --> F[Publikacja w kanałach cyfrowych]

    %% Oddzielny proces dla social media
    B --> G[Publikacja w mediach społecznościowych]
    G --> H[Okresowy przegląd treści opublikowanych w mediach społecznościowych]
    H -->|Braki| I[Informacja zwrotna do autora + ustalenie terminu poprawek]
    I --> H[Okresowy przegląd treści opublikowanych w mediach społecznościowych]
    H -->|OK| E[Akceptacja]
