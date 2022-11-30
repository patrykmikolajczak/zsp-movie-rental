# Wypożyczalnia filmów
Do stworzenia wypożyczalnia filmów.

## Nowe elementy
include

## Spis widoków (stron)
### Ogólno dostępne  
#### Bez logowania
strona główna - index.php  
szczegóły filmu - movie-details.php  
wyszukaj film - movie-search.php  
logowanie - login.php  
rejestracja - logout.php  
#### Po logowaniu
dodawanie nowego filmu - movie-add.php
moje filmy - movie-my.php

### Tylko dla administratora (tylko po zalogowaniu jako administrator)
lista filmów - movie-list.php  
lista filmów jeszcze nie zaakceptowanych - movie-list.php&  
szczegóły filmu - movie-details.php  
logowanie - login.php  
rejestracja - logout.php  

## Struktura projektu
Struktura którą trzeba stworzyć w projekcie  

```
.  
├── index.php  
├── css
│   ├── style.css
├── includes
│   ├── footer.php
│   ├── header.php
│   └── nav.php
├── sites
│   ├── movie-details.php
│   ├── movie-search.php
│   ├── movie-add.php
│   ├── movie-my.php
│   ├── login.php
│   └── logout.php
├── admin
│   ├── movie-list.php
│   ├── movie-details.php
│   ├── login.php
│   └── logout.php
```

## Baza danych
Projekt musi pozwalać na dodanie użytkownika, dodanie użytkownika który może być administratorem.
Dodanie filmu i możliwość jego zatwierdzania (fil zanim pojawi się na liście ogólnodostępnej musi być zaakceptowany przez administratora)

## Część I
Sprawdź czy stworzona baza spełnia wymmagania:  
1NF  
2NF  
3NF  
https://dbadmin.net.pl/normalizacja-baz-danych-czym-jest-postac-normalna/

## Część II
Stwórz stronę do wypożyczania filmów.
Strona musi pozwalać na swobodne przeglądanie dostępnych filmów.  
Musi ograniczyć dostęp do obszarów zabronionych bez logowania.  
Musi pozwalać na wypożyczenie filmu, ale tylko osobą zalogowanym.  
Musi pozwalać na zaakceptowanie przez administratora filmu wypożyczanego przez użytkownika.  
