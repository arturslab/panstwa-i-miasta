# Państwa i Miasta 🎲

**[Otwórz aplikację](https://arturslab.github.io/panstwa-i-miasta/)**

Aplikacja webowa wspomagająca grę **Państwa i Miasta** — losuje literę rundy z animacją i obsługuje odliczanie czasu.

## Funkcje

- **Losowanie litery** — efektowna animacja slot-machine, litera zajmuje pół ekranu
- **Wykluczanie wylosowanych liter** — każda wylosowana litera trafia do tabelki; kolejne losowania pomijają już użyte litery
- **Licznik rund** — automatycznie rośnie po każdym losowaniu
- **Odliczanie 10→0** — uruchamiane gdy pierwszy gracz skończy; ostatnie 3 sekundy pulsują na czerwono, na końcu pojawia się „Sprawdzam!"
- **Nowa gra** — czyści wylosowane litery i resetuje rundę
- **Dźwięki** — syntezowane przez Web Audio API (klikanie podczas losowania, fanfary po wylosowaniu, tiki odliczania)
- **PWA** — działa offline, można zainstalować na telefonie/tablecie

## Użycie

Otwórz stronę i kliknij **START** aby wylosować literę. Po zakończeniu rundy kliknij **Odliczaj** aby uruchomić timer dla pozostałych graczy.

## Technologie

Czysty HTML + CSS + JavaScript — bez żadnych zależności ani bundlerów.
