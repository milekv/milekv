<p align="center">
  <img src="./assets/profile-header.svg?v=5" width="100%" alt="Miłosz Kordziński — SQL i narzędzia bazodanowe" />
</p>

<p align="center">
  <a href="./README.md">English</a> · <strong>Polski</strong><br />
  <a href="https://milekv.github.io/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/milosz-kordzinski-a85947254">LinkedIn</a> ·
  <a href="https://github.com/milekv?tab=repositories">Repozytoria</a>
</p>

Na co dzień przygotowuję raporty SQL i sprawdzam dane w systemach uczelnianych. Tutaj tworzę narzędzia do tych części pracy z bazą, w których łatwo coś przeoczyć: analizy zapytań, planów wykonania i ryzyka migracji. Najczęściej używam PostgreSQL, Oracle i TypeScriptu.

### Nad czym pracuję

**[SQL Atlas](https://github.com/milekv/sql-atlas)** — sprawdzanie SQL w [przeglądarce](https://milekv.github.io/sql-atlas/), VS Code, terminalu i CI. Narzędzie wskazuje znalezione problemy w kodzie i pozwala przeglądać plany wykonania PostgreSQL, SQL Server oraz Oracle. Analiza działa lokalnie i nie uruchamia zapytań.

<a href="https://milekv.github.io/sql-atlas/"><img src="./assets/sql-atlas-tour.gif" width="100%" alt="Trzy rzeczywiste zrzuty SQL Atlas: analiza zapytania, propozycje indeksów i EXPLAIN PostgreSQL" /></a>

<sub>Rzeczywiste zrzuty aplikacji z repozytorium SQL Atlas. [Wypróbuj](https://milekv.github.io/sql-atlas/) · [Przeczytaj dokumentację](https://github.com/milekv/sql-atlas/blob/main/README.pl.md)</sub>

**[pg-migration-guard](https://github.com/milekv/pg-migration-guard)** — kontrola plików migracji PostgreSQL przed wdrożeniem. Wskazuje wybrane ryzyka związane z blokadami, przepisywaniem tabel i utratą danych. Opcjonalnie odczytuje metadane katalogu bazy, bez wykonywania migracji. [Sprawdziłem narzędzie na 760 plikach migracji](https://dev.to/milekv/i-tested-a-postgresql-migration-checker-on-760-real-migration-files-4d9h) i opisałem, czego można się dowiedzieć z wyników, a czego nie.

### Pozostałe projekty

| Projekt | Co można sprawdzić |
| --- | --- |
| [Ask Database](https://github.com/milekv/ask-database) | Kontekst schematu PostgreSQL, tworzenie SQL z uwzględnieniem relacji i walidacja zapytań. [Demo](https://milekv.github.io/ask-database/) |
| [VisualDB Studio](https://github.com/milekv/visualdb-studio) | Wizualne modelowanie schematu PostgreSQL, relacje, walidacja i generowanie DDL. [Demo](https://milekv.github.io/visualdb-studio/) |
| [OraBank](https://github.com/milekv/oracle-bank-system) | Transakcje Oracle SQL/PLSQL, blokady, audyt i scenariusze odtwarzania. [Opis techniczny](https://milekv.github.io/orabank-site/) |

### Wkład w open source

Do projektu **nplusone** dodałem obsługę [SQL Server](https://github.com/Truta446/nplusone/pull/29) oraz adapter [libSQL/Turso](https://github.com/Truta446/nplusone/pull/13). Obie zmiany, wraz z testami, zostały scalone przez autorów projektu.

Na co dzień używam PostgreSQL, Oracle, SQL Server, TypeScriptu, Reacta, Node.js i GitHub Actions. Rozwijam się w kierunku inżynierii danych i chmury; szczególnie interesują mnie plany wykonania i wydajność potwierdzona pomiarami.
