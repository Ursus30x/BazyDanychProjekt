# PROJEKT BAZY DANYCH

## Klient
Klientem projektu jest gabinet dentystyczny **"Ząbek"**.

## Cel bazy danych i problemy do rozwiązania
Problemem jest nielad w dokumentacji pacjetow, pracownikow oraz ksiegowosci (zaplata za uslugi, odprowadzenie podatku i wizty oplacone z NFZ).

Celem projektu jest usprawnienie funkcjonowania gabinetu dentystycznego poprzez automatyzację procesów rezerwacji oraz płatności za wizyty.
System umożliwi:

- Kategoryzację usług,
- Szybka rezerwacje terminow,
- Stworzenie spisu pracowników gabinetu,
- Stworzenie spisu pacjentow gabinetu,
- Usprawnienie komunikacji,
- Biezaca inwetaryzacja materialow oraz narzedzi w gabiencie.

## Użytkownicy systemu i wspierane stanowiska
System będzie wspierał różne stanowiska pracy w gabinecie:

- **Recepcjoniści**: Dzięki łatwemu dostępowi do danych pacjentów i funkcji rezerwacji wizyt, alokowanie czasu w harmonogramie będzie szybsze i bardziej intuicyjne.
- **Stomatolodzy**: System zapewni szybki dostęp do informacji o pacjentach, ułatwiając planowanie dyżurów i interakcje z pacjentami.
- **Księgowi**: Automatyzacja rozliczeń wizyt pozwoli na łatwiejsze monitorowanie płatności i generowanie raportów.

## Scenariusze uzycia
- **Pan Michal musi przelozyc wizyte u detystki Anety, dzwoniac na recepcje prosi Pania Marysie o przelozenie na najblizszy nastepny termin. System znajduje Pani Marysi najblizszy termin do Pani Anety oraz opcjonalne terminy z innymi dentystami. Dodatkowo zmiana w systemie powoduje wyslanie SMSa z potwierdzeniem do Pana Michala.
- Dentysta Mariusz wykonuje plombowanie zeba, przeszukujac szafke z materialem nie moze znalezc odpowiedniej plomby. Otwierajac nasza aplikacje dowiaduje sie ze material znajduje sie na zapleczu w szafce numer 6, polce 3
- Pani Katarzyna przetwarzala rachunki za ostatni miesiac, do tego potrzebowala przychodow oraz kosztow gabinetu z ostatniego miesciaca. Nasz system umozliwil szybkie wyswietlenie zestawienia wraz z wstepnymi wyliczeniami podatku.

## Zapytania?

- Ile godzin dentysta Mariusz Lubomirski przepracowal w 2021 roku?

- Ile pajcetow z nazwiskiem na A zostalo obsluzonych przez pania Anete Jeziorska?

- Ile zarobil gabinet na poszczegolnych dentystach? 

- Podaj numer PESEL oraz nazwisko pacjeta ktory zaplacil najwiecej za wizyty w roku 2007

- Ile danego materialu zeszlo w ciagu poprzedniego miesiaca?


## Wykluczenia
W sklad bazy nie bedzie wchodzilo:
-  **Brak historii zdrowotnej pacjenta spoza gabinetu.**  
Baza nie będzie zawierać danych dotyczących zabiegów i leczenia pacjentów w innych placówkach.

- **Brak szczegółowych danych personalnych pracowników.**  
    System nie będzie przechowywać danych osobowych pracowników, takich jak adresy zamieszkania czy numery kont bankowych.

- **Brak danych o rodzinach pacjentów.**  
    System nie będzie gromadził informacji o członkach rodziny pacjentów, takich jak numery kontaktowe lub powiązania rodzinne.