# Chronicon — źródła do rozwoju postaci i prowadzenia repo

**Sprawdzono linki:** 20.10.2026. **Nasza gra:** 1.61.x. **Priorytet:** tooltip z gry > aktualny materiał dla 1.61 > starsza baza/poradnik.

## Oficjalne i rekomendowane przez twórcę

| Źródło | Link | Do czego służy | Zastrzeżenie |
|---|---|---|---|
| Strona gry na Steam | https://store.steampowered.com/app/375480/Chronicon/ | Informacje o grze, dodatkach, aktualizacjach | Nie jest atlasem skilli |
| Community Resources — wątek przypięty przez twórcę | https://steamcommunity.com/app/375480/discussions/0/3083256496974241248/ | Punkt startowy do baz, build-plannera i poradników | Lista z 2021 r.; linki i wersje mogą się zestarzeć |
| Chronicon DB | https://chronicondb.com/items | Wyszukiwanie przedmiotów, mocy i enchantów | Weryfikować działanie i aktualność |
| Chronicon Builder / Chronomancer | http://iconmaster.info/Chronomancer/ | Planowanie buildów | Starszy projekt; sprawdzić dostępność i wersję przed użyciem |
| Poradniki Steam — klasy | https://steamcommunity.com/app/375480/guides/?requiredtags%5B%5D=Classes&requiredtags%5B%5D=English | Buildy, progresja, ekwipunek; szukać 1.61 | Autorzy społecznościowi; różne wersje i etapy gry |
| Wszystkie poradniki Steam | https://steamcommunity.com/app/375480/guides/ | Runes, craft, transmutation, leveling, endgame | Zawsze sprawdzić datę i patch |

## Dane historyczne — NIE jako potwierdzenie 1.61

| Źródło | Link | Zastosowanie |
|---|---|---|
| ChroniconDB — dane skilli 1.52.0 | https://github.com/gabriel-dehan/chronicondb-client/blob/main/src/engine/data/1.52.0/sources/skilldata_1.52.0.json | Historyczna geometria drzewek i indeks umiejętności; wszystkie liczby do weryfikacji |
| ChroniCalc — eksport opcji | https://github.com/MidwestSteeze/ChroniCalc/blob/master/ChroniCalc/Assets/Data/convertjson.xml | Archiwalna mapa wariantów Mastery, może pomijać nowe opcje |
| ChroniCalc — logika aplikacji | https://github.com/MidwestSteeze/ChroniCalc/blob/master/ChroniCalc/MainForm.cs | Interpretacja współdzielonych pól Mastery |
| Chronicon Wiki (Fandom) | https://chronicon.fandom.com/wiki/Chronicon_Wiki | Ogólne mechaniki i lokalizacje; sama wiki ostrzega o nieaktualnych danych |

## Materiały o buildach — inspiracja, nie instrukcja 1:1

- https://www.wilfridwong.com/2020/09/09/chronicon-guides/ — zbiór poradników, w tym Warlock; materiały historyczne.
- https://smattymattyca.wordpress.com/2022/03/20/chronicon-warlock-build-guide-sun-moon-deathbringer/ — przykładowy Warlock Frost, **inny build** niż nasz Poison Corruptor.
- https://steamcommunity.com/app/375480/guides/?requiredtags%5B0%5D=Classes&requiredtags%5B1%5D=English — wyszukiwanie poradników klasowych, w tym nowszych oznaczonych 1.61.

## Procedura przed wydaniem punktów

1. Odczytaj **WARLOCK_PROGRESS.md** i aktualną liczbę punktów; nie myl planu z wykonanym zakupem.
2. Zidentyfikuj skill i jego wymagania w **WARLOCK_SKILL_TREES.md** albo **WARLOCK_MASTERY_TREE.md**.
3. Jeśli dane pochodzą z archiwum, sprawdź aktualny tooltip 1.61 ze zrzutu gracza; bez tego nie twierdź, że liczby są pewne.
4. Zaproponuj konkretny przydział z uzasadnieniem synergii Poison/Infection i przeżywalności.
5. **Dopiero po potwierdzeniu wydania** zaktualizuj punkty, rangi, przyciski i datę w **WARLOCK_PROGRESS.md** oraz krótkie podsumowanie w **README.md**.
6. Nowe potwierdzone opisy dopisuj do odpowiedniego atlasu z datą i źródłem (np. screenshot 20.10.2026). Nie nadpisuj bez śladu starszych danych.

## Status źródeł

Samo znalezienie linku nie oznacza zweryfikowania wszystkich danych na stronie. W razie rozbieżności obowiązuje ekran gry 1.61.x. Nie traktuj poradnika endgame jako optymalnej kolejności punktów dla postaci na niskim poziomie.
