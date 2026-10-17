# Warden — aktualny stan postaci

Ten plik jest **jedynym źródłem prawdy o aktualnym stanie naszego bohatera**. Aktualizujemy go po każdej zmianie punktów, aktywnych skilli, przypisania do pada albo ważnego elementu buildu.

**Tryb:** Hardcore  
**Postać:** Warden — łucznik  
**Poziom ostatnio potwierdzony na screenie:** 3  
**Wolne Skill Points (najnowsze zgłoszenie):** 1  
**Główne drzewko:** Wind Ranger / Physical  
**Docelowy kierunek:** High Ranger / Rapid Shot / Splinter / Double Draw / Razor Tips

## Aktualnie POTWIERDZONE zainwestowane punkty

| Drzewko | Skill | Punkty | Użycie |
|---|---|---:|---|
| Wind Ranger | **Rapid Shot** | 2 | główny atak, **RT** |
| Wind Ranger | **Tumble** | 1 | mobilność / unik, **B** |
| Wind Ranger | **Archer** | 1 | pasywka zwiększająca obrażenia skilli Archery |
| Wind Ranger | **Multi Shot** | 1 | obszarowy wachlarz strzał, **LT** — potwierdzone przypisanie przez gracza |
| Druid | **Leaf Wind** | 1 | regeneracja zdrowia; cel **RB** (przypisanie niepotwierdzone) |

**Łącznie potwierdzone wydane punkty:** 6

## Aktualny wolny punkt

Użytkownik potwierdził, że **wydał drugi z dwóch wcześniejszych punktów w Leaf Wind**. Zapisany stan: **Rapid Shot 2 / Tumble 1 / Archer 1 / Multi Shot 1 / Leaf Wind 1**, łącznie **6 wydanych punktów**. Zgłosił **1 kolejny wolny punkt**.

**Do rozstrzygnięcia:** gdzie najlepiej wydać nowy punkt; porównać odblokowane w grze progi Wind Ranger, szczególnie **Splinter**, **Overdraw**, **Readiness**, ewentualnie **Gale**, z dostępnymi defensywnymi pasywkami. Nie zaznaczać jako wydany, dopóki użytkownik nie potwierdzi.

## Pad — potwierdzone przypisania i plan

| Przycisk | Umiejętność / oczekiwana funkcja | Stan |
|---|---|---|
| **RT** | **Rapid Shot** — podstawowy atak z łuku | **Potwierdzone przypisanie** |
| **B** | **Tumble** — przewrót / unik | **Potwierdzone przypisanie** |
| **LT** | **Multi Shot 1** — atak na grupy przed postacią; ewentualny Gale później | **Potwierdzone przypisanie przez gracza** |
| **RB** | **Leaf Wind 1** — wyuczone leczenie, docelowo na RB | **Punkt wydany; przypisanie do RB jeszcze niepotwierdzone** |
| **Y** | wolny slot | **Do dyspozycji** |
| **LB** | wolny slot | **Do dyspozycji** |

### Kryteria wyboru kolejnych skilli aktywnych (Hardcore)

- **LT (ratunek przed otoczeniem):** pierwszeństwo ma szeroki obszar działania i/lub odrzucenie wrogów. **Gale** jest kandydatem do zweryfikowania w aktualnym drzewku (twistery i knockback); **Multi Shot** to raczej wachlarz strzał przed postacią, więc może gorzej pomagać przy całkowitym otoczeniu. Nie zakładać, że są już odblokowane.
- **RB (leczenie):** rozważyć **Leaf Wind** z Druida (regeneruje życie w czasie). Jeżeli nie jest jeszcze dostępne, do chwili odblokowania szukać innego źródła leczenia; **Root Veil** jest tarczą, a nie leczeniem.
- **Y i LB:** na razie pozostają wolne; później dobierzemy umiejętności pod kontrolę, buff, defensywę albo mocniejszy atak.
- Wydawanie punktów powinno od teraz uwzględniać **wcześniejsze odblokowanie sensownego LT i RB**, bez porzucania rdzenia Rapid Shot / Splinter / Double Draw / Razor Tips.

**Rozróżnienie:** „potwierdzone przypisanie” = użytkownik już tak gra; „życzenie” = plan na przyszłość. Nie zapisujemy planowanego skilla jako wyuczonego lub przypisanego przed potwierdzeniem.

## Rozważane: Multi Shot na RT i automatyczne używanie skilli (17.10.2026)

**Nowe pytanie gracza:** czy lepiej przenieść **Multi Shot** na **RT** i używać jako głównego ataku? Przypomnienie: w Chronicon istnieje oficjalna funkcja **Auto Cast**.

**Rekomendacja na teraz — bez zmiany potwierdzonego przypisania:**
- **RT: Rapid Shot**, główny, szybki atak dla rdzenia High Ranger / Splinter / Double Draw / Razor Tips.
- **LT: Multi Shot**, planowany dodatkowy ostrzał grup przed bohaterem; docelowo do rozważenia Gale jako AoE z knockback. Możemy przetestować Multi Shot na RT później, jeżeli gracz zechce porównać styl.
- **RB: Leaf Wind**, planowane leczenie **ręczne** — pozostawiamy je na potrzebę, nie na Auto.
- **B: Tumble**, unik **ręczny**, nigdy Auto na Hardcore (przypadkowe przeturlanie może zabić).
- **Y/LB: wolne**; później warto rozważyć umiejętności wzmacniające lub ofensywne z **Auto**, po sprawdzeniu kosztu many, cooldownu i bezpieczeństwa.

**Auto Cast — oficjalna mechanika od update'u 1.53.0:**
1. W drzewku umiejętności wejść w menu przypisywania umiejętności do slotu.
2. Włączyć opcję **Auto** dla wybranego skilla.
3. W trakcie gry nacisnąć przypisany przycisk na padzie, aby **przełączyć Auto ON/OFF**.
4. Przy Auto ON gra używa umiejętności samoczynnie, gdy jest dostępna po cooldownie; przy aktywnym Auto pasek umiejętności pokazuje znacznik.
5. Auto nie oznacza, że mamy automatycznie włączać wszystko. Ostrożnie z dużym kosztem many, leczeniem i przemieszczaniem.

Źródła mechaniki:
- Oficjalne patch notes 1.53.0: https://steamdb.info/patchnotes/19753965/
- Potwierdzenie od dewelopera Squarebit, 29.10.2025: https://steamcommunity.com/app/375480/discussions/0/597415740309810979/

**Aktualizacja po dalszej rozmowie:** Multi Shot potwierdzony na LT. Leaf Wind 1 potwierdzony jako wyuczony; przypisanie do RB wymaga potwierdzenia. Auto Cast nie został potwierdzony jako włączony.

---

## Kolejność sprawdzania przed następną decyzją

1. `WARDEN_PROGRESS.md` — co naprawdę mamy teraz.
2. `WARDEN_ALL_TREES.md` — wszystkie cztery specjalizacje + Mastery.
3. `WIND_RANGER_SKILL_TREE.md` — szczegóły głównego drzewka.
4. `WARDEN_HARDCORE_ARCHER.md` — plan buildu i ekwipunku.

## Co aktualizujemy po KAŻDEJ zmianie bohatera

- poziom,
- wolne Skill Points,
- każdy skill i liczba punktów,
- drzewko, w którym leży skill,
- aktywne skille i przypisanie do pada,
- nową specjalizację / Mastery,
- ważne zmiany ekwipunku dla buildu,
- kluczowe sety, gemy i runy,
- istotne problemy: brak many, przeżywalność, zbyt mały damage itp.,
- ostatnią decyzję i rekomendowany kolejny krok.

## Dziennik zmian

### 17.10.2026

- **Najnowsze potwierdzenie:** gracz wydał punkt w **Leaf Wind 1 (Druid)**, czyli łącznie mamy **6 potwierdzonych punktów wydanych**. Zgłosił **1 kolejny wolny punkt**. Przypisanie Leaf Wind do RB jeszcze niepotwierdzone.

- **Nowe potwierdzenie:** użytkownik zostawia przyciski bez zmian i jednoznacznie potwierdza **Multi Shot na LT**. Zapisano **Multi Shot 1** jako wyuczony/przypisany, **5 potwierdzonych punktów wydanych**.
- **Drugi punkt z ostatniej dwójki:** brak jednoznacznego potwierdzenia Leaf Wind/RB; wymaga dopytania. Nie zapisujemy go jako wydanego.
- **Stała zasada pracy:** po każdym zgłoszonym i potwierdzonym wydaniu punktu albo zmianie ekwipunku/przypisania od razu aktualizujemy ten plik w repo w tej samej rozmowie. Rozróżniamy potwierdzone od rekomendowanych.

- Doprecyzowano wymagania dla sterowania padem: **LT = obszarowy ratunkowy atak przy otoczeniu**, **RB = leczenie**, **B = Tumble**, **RT = Rapid Shot**; **Y i LB pozostają wolne**.
- LT i RB są na razie **celami buildu**, nie potwierdzonymi przydziałami skilli. Następne decyzje o punktach mają uwzględniać ich odblokowanie.

- Potwierdzony wcześniejszy stan: Rapid Shot 1 / Tumble 1 / Archer 1.
- Użytkownik zgłosił **1 nowy wolny punkt**.
- Rekomendacja: **Rapid Shot 1 → 2**.
- Użytkownik potwierdził wydanie punktu: **Rapid Shot ma 2 punkty**. Wydanych łącznie 4.
- Nowe zgłoszenie: **2 wolne punkty**.
- Nowa rekomendacja: **Multi Shot 1 na LT oraz Leaf Wind 1 na RB**. Multi Shot na LT potwierdzony; Leaf Wind / RB niepotwierdzony.

---

**Zasada:** niczego nie uznajemy za założone, wydane lub przypisane tylko dlatego, że zostało zarekomendowane. Do sekcji „potwierdzone” trafia dopiero po informacji lub screenie z gry.