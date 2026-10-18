# Warlock — roboczy build do kampanii: Corruptor / Infection / Poison Nova

**Gracz zaczął grać Warlockiem 17.10.2026.** Od tej postaci gramy **bez Hardcore**. Nasza zasada rotacji: po zgonie zmieniamy klasę, więc nadal warto dbać o przeżywalność. Żadne punkty ani przyciski tego pliku nie są potwierdzonym stanem postaci — faktyczny stan jest w WARLOCK_PROGRESS.md.

## Pomysł i uzasadnienie

**Główne drzewko: Corruptor (Poison).** Warlock ma zamieniać całe grupy przeciwników w jedną rozprzestrzeniającą się zarazę: zaklęcia AoE nakładają Infection, Bursting Boils i Contagion przenoszą ją dalej, a Outbreak daje eksplozje przy śmierci wrogów. To bardzo dynamiczna alternatywa dla Wardena; nie wymaga specjalnego legendarnego sprzętu na samym początku.

**Dodatki:** Reaper do leczenia i Health on Hit, Lich do teleportacji Soul Warp, Demonologist do Damage Reduction. Nie rozrzucamy na starcie punktów bez planu. Konkretny wybór zawsze zależy od progu dostępności na screenie.

## Projekt pada — do potwierdzenia, nie jest wykonany

| Przycisk | Docelowy skill | Cel | Auto? |
|---|---|---|---|
| **RT** | **Blood Curse** (Corruptor) | bazowy atak AoE Poison, zadaje również DoT | nie — główny manualny |
| **LT** | **Flesh Rot 1** (Corruptor), później **Poison Nova** gdy dostępna | klątwa Poison AoE nakładana na grupy, później nova wokół postaci | nie — używamy świadomie |
| **RB** | **Soul Eater 1** (Reaper) — **wyuczony, przypisanie RB niepotwierdzone** | szybkie leczenie za **1 Soul**, w 1.52 ranga 1 przywraca 10% max HP | nie — awaryjny |
| **B** | **Soul Warp 1** (Lich) — **wyuczone i POTWIERDZONE na B** | teleport odciągający nas od zagrożenia; zwiększony zasięg kosztem dusz | ręcznie — awaryjny |
| **Y** | Zombie lub Plague Bearer / opcjonalnie Plague | wsparcie na grupy; jeśli companion jest aktywny w slocie, użycie może mieć dodatkowy efekt kosztujący Soul | Auto ewentualnie po sprawdzeniu |
| **LB** | Ritual of Souls / Plague / inny buff | stała korzyść lub wygodny autocast | tylko gdy ekonomia dusz/many na to pozwala |

**Priorytet użytkownika z poprzedniej postaci:** RT dobry główny atak, LT AoE na otoczenie, RB leczenie, B ruch/unik; Y/LB do dalszych funkcji. Wszystko do potwierdzenia podczas gry Warlockiem. **Auto Cast** jest użyteczny dla buffów i skilli, które mogą bezpiecznie działać z cooldownu, ale nie dla leczenia i awaryjnego przemieszczenia.

## Najbliższe etapy i punkty — priorytety, nie automatyczne wydanie

### Poziomowanie, etap 1: pierwsze kilka punktów
1. **Blood Curse 1 (Corruptor)** — cel na pierwszy ofensywny punkt, jeśli jeszcze niewydany. Zastępuje podstawowy atak, ma małe AoE i DoT; na RT.
2. **Infection 1** — odblokować, gdy aktywne: wszystkie Poison skille nakładają kolejne DoT.
3. **Epidemic 1** — Attack Speed, poprawia komfort czarowania; później wyższe rangi.
4. Kolejne punkty tak rozkładać, żeby otwierać następny poziom Corruptor; **nie maksować wszystkiego od razu**, jeśli blokuje to dojście do silnego AoE.

### Etap 2: obszar i rozprzestrzenianie
1. **Flesh Rot 1** lub **Plague 1** jako pomost po odblokowaniu: Flesh Rot rozchodzi się między przeciwnikami; Plague trzyma chmurę trucizny blisko postaci.
2. **Bursting Boils 1** po Infection — wzmacnia obrażenia na grupach.
3. **Poison Nova 1** kiedy dostępne — przede wszystkim **LT**. W danych 1.52 ma duży promień, uderza wszystkich dookoła.
4. **Contagion** / **Outbreak** — łańcuchowe rozprzestrzenianie Infection i eksplozje zakażonych po zabiciu.
5. Stopniowo rozwijamy **Poison Nova, Infection, Bursting Boils, Outbreak, Blood Curse** według realnych obrażeń i odblokowanych rang.

### Etap 3: przeżywalność i wygoda
- **Soul Eater 1 (Reaper)** na RB: leczenie za Soul; nie spamować bez zapasu dusz. W danych 1.52 ranga 1 to 10% Max Health.
- **Soul Warp 1 (Lich)** na B: teleport; oszczędzamy część dusz na wyjście z tarapatów.
- **Undeath** oraz **Vampirism** (Reaper) jako HP/Health on Hit.
- **Demon Skin** (Demonologist): nawet 1 punkt daje w danych 1.52 +6% Damage Reduction, mocny wybór, jeśli są problemy z przetrwaniem.
- **Soul Feast** (Reaper) na później przy sprawnej produkcji dusz.
- **Zombie / Plague Bearer** z Corruptor — 1 punkt w towarzysza, jeśli zrobi się zbyt ciasno; lepiej nie od razu kosztem kluczowych efektów Poison.

## NAJNOWSZY STAN — Bursting Boils 3/3 POTWIERDZONE (18.10.2026)

**14 zwykłych Skill Points WYDANYCH, 0 wolnych:**
- **Corruptor = 12:** Blood Curse 4/5, Epidemic 1/5, Infection 3/3, Flesh Rot 1/5, **Bursting Boils 3/3 MAX**.
- **Lich:** Soul Warp 1 (przypisany B — potwierdzone). **Reaper:** Soul Eater 1 (leczenie 10% maks. HP, 36 s cooldown; RB nadal niepotwierdzone).
- **Mastery:** Poison zielona czaszka, R1-K1 Corruptor **ranga 2**, 2 punkty Mastery wydane, 0 wolnych.
- Bursting Boils działa pasywnie, wg aktualnego tooltipa ranga maks. to **20% szansy** wyzwolenia obrażeń Infection w **3,6 m**.
- **Plan na NASTĘPNY zdobyty punkt (nie teraz):** sprawdzić w grze, czy odblokowano **Contagion** (pasywny spread) lub **Poison Nova** (aktywny AoE wokół bohatera), zgodnie z naszym celem, oraz dalej **Outbreak**. Nie oznaczać żadnego z nich jako wyuczonego przed faktycznym potwierdzeniem.
- **Zagadka 9 kryształów nadal nierozliczona:** na zdjęciu układ BYR/YBR/BYR. Obliczona sekwencja przesunięć cyklicznych: górny rząd w lewo → środkowa kolumna w górę → środkowy rząd w prawo → lewa kolumna w dół. Wynik BBB/YYY/RRR, o ile stan gry się nie zmienił.

## HISTORIA — NAJNOWSZY STAN — Bursting Boils 2 POTWIERDZONE, 1 NOWY zwykły punkt (18.10.2026)

- **13 potwierdzonych zwykłych punktów wydanych, 1 nowy wolny.**
- **Corruptor (11 punktów):** Blood Curse 4, Epidemic 1, Infection 3/3, Flesh Rot 1, **Bursting Boils 2/3 (POTWIERDZONE)**.
- **Lich:** Soul Warp 1 — **B (potwierdzone)**. **Reaper:** Soul Eater 1 — przypisanie RB niepotwierdzone.
- **Mastery:** Poison (zielona czaszka Corruptor R1-K1) **ranga 2**; 2 punkty Mastery wydane, 0 wolnych.
- **REKOMENDACJA NA AKTUALNY 1 WOLNY PUNKT: Bursting Boils 2→3 (NIE WYDANE).** W tooltipie gry 1.61 maksymalna ranga oznacza **20% szansy** rozlania obrażeń Infection w promieniu **3,6 m**. Po kupieniu 3/3 Corruptor osiągnie **12 punktów**; wtedy sprawdzić odblokowanie **Contagion / Poison Nova**, następnie Outbreak.
- **Po POTWIERDZONYM wydaniu punktu** bilans wyniesie 14 wydanych / 0 wolnych. Do tego momentu **nie wpisywać** Bursting Boils 3 ani innych planowanych umiejętności jako wykonanych.

## HISTORIA — NAJNOWSZY STAN — Bursting Boils 1 potwierdzony, 1 zwykły punkt wolny (18.10.2026)

**Potwierdzono 12 zwykłych punktów wydanych, 1 nowy wolny:**
- Corruptor: Blood Curse 4, Epidemic 1, Infection 3, Flesh Rot 1, **Bursting Boils 1/3** (łącznie 10 punktów w Corruptor).
- Lich: Soul Warp 1, przypisanie do B potwierdzone.
- Reaper: Soul Eater 1, przypisanie RB niepotwierdzone.
- Mastery: **Poison zielona czaszka Corruptor R1-K1 ranga 2**, 2 wydane, 0 wolnych.

**Następny 1 WOLNY punkt — rekomendacja jeszcze NIEWYKONANA: Bursting Boils 1→2**. Działa pasywnie dla Infection i nie potrzebuje przypisania do pada. Dopiero po potwierdzeniu będzie 13 punktów wydanych i 0 wolnych.

**Dalszy rozwój:** Contagion / Outbreak / Poison Nova, zgodnie z odblokowaniami. Sformułowanie użytkownika „na b wydany” dotyczy zakupienia **Bursting Boils 1**, nie zmiany przypisania teleportu do B.

## HISTORIA — Mastery Poison 2 POTWIERDZONE i nowy zwykły punkt (18.10.2026)

- **Mastery:** użytkownik potwierdził rozwinięcie **Poison zielona czaszka R1-K1 Corruptor z rangi 1 na 2**; **2 Mastery Points wydane / 0 wolnych**. Stary eksport mówi +4% Poison Damage przy rangach 2, ale tooltip 1.61 procentowo niepotwierdzony.
- **Zwykłe umiejętności:** ostatni **potwierdzony** stan to **11 Skill Points wydanych**: Corruptor Blood Curse 4 / Epidemic 1 / Infection 3 / Flesh Rot 1 = 9, Lich Soul Warp 1, Reaper Soul Eater 1.
- Poprzednio gracz otrzymał **1 wolny zwykły punkt** i rekomendowano Bursting Boils 0→1, ale **nie potwierdził wydania**. Teraz zgłosił **kolejny nowy zwykły punkt**; jeżeli wcześniejszego nie wydał, możliwe że ma 2 wolne; jeżeli wydał w Bursting Boils, ma 1 wolny i Bursting Boils 1/3. **Bez potwierdzenia nie wpisujemy żadnej z tych wersji jako faktu.**
- **Rekomendacja:** jeśli Bursting Boils = 0/3, **pierwszy punkt tam (0→1)**. Jeśli Bursting Boils = 1/3, **kolejny punkt tam (1→2)**. To pasywka z Infection, nie wymaga przycisku. W 1.61 jej pierwsza ranga daje 10% szansy i promień 2.2 m. Potem Contagion i Outbreak.
- W razie wątpliwości gracz powinien przesłać zrzut umiejętności, żeby zweryfikować liczbę wolnych punktów oraz Bursting Boils.

## HISTORIA — stan z Lv. 11 / M1 przed potwierdzeniem Bursting Boils

**Potwierdzono 11 zwykłych punktów WYDANYCH.** Wcześniejszy 1 zwykły punkt miał niepotwierdzone wykorzystanie, a teraz gracz zgłosił kolejny NOWY wolny punkt.
- Corruptor: **Blood Curse 4**, Epidemic 1, **Infection 3/3**, Flesh Rot 1 = **9 punktów**.
- Lich: Soul Warp 1 (przypisanie **B potwierdzone**).
- Reaper: Soul Eater 1 (umiejętność potwierdzona, rzeczywiste RB nie).
- Mastery: **2 punkty WYDANE w Poison (zielona czaszka, R1-K1 Corruptor), ranga 2**, 0 wolnych Mastery.

### Bursting Boils — gotowość do następnego awansu

Najnowszy wcześniejszy screen wersji 1.61 podał wymóg **„Requires 9 points spent to unlock”** dla Bursting Boils. Kupując Blood Curse 4 osiągnęliśmy **9 punktów Corruptor**; zatem **próg inwestycji jest spełniony**, lecz gracz nie pokazał jeszcze ekranu węzła po odblokowaniu.

**BIEŻĄCA rekomendacja — bez potwierdzenia wykonania:** **Bursting Boils 0→1**, jeśli nadal ranga 0; **Bursting Boils 1→2**, jeśli gracz zdążył wydać poprzedni punkt. Skill pasywny, bez przypisania do pada. W wersji 1.61 zgodnie ze screenem: **10%** szansy na wyzwolenie obrażeń Infection w promieniu **2.2 m** po trafieniu Poison zakażonego przeciwnika; maks. poziom 20% / 3.6 m. Stare dane 1.52 mówią 12% na pierwszej randze — **najnowszy tooltip 10% ma pierwszeństwo**.

**Po Bursting Boils** wracamy do Contagion / Poison Nova / Outbreak. **Nie wpisywać Bursting Boils 1 ani 2 jako wyuczonych przed potwierdzeniem od gracza.** Mastery: 2 wydane, 0 wolnych. Bilans zwykłych: 11 wydanych potwierdzonych, potencjalnie 2 wolne (1 nowy i 1 poprzedni bez potwierdzenia wykorzystania).

**Pad:** RT Blood Curse i LT Flesh Rot planowane, ale niepotwierdzone; RB Soul Eater wyuczone, faktyczne przypisanie niepotwierdzone; **B Soul Warp potwierdzone**.

## Ekwipunek i statystyki w kampanii

- Broń: **Poison Damage / Damage / Attack Speed**, później efekty Infection i zwiększające **Reach**.
- Obrona: **Health, All Resistances, Damage Reduction, Evasion, Health on Hit** — brak permadeath nie oznacza, że chcemy często ginąć.
- Mana: nie przeciążać paska zbyt kosztownymi czarami; uzupełniać Mana on Hit / regeneration według potrzeby.
- Przy porównywaniu itemów patrzeć na faktyczne działanie **Blood Curse / Poison Nova**, nie sam poziom przedmiotu.
- Niezależnie od teoretycznej mety, jeśli wpadnie silny legendarny set Fire/Frost/Shadow możemy rozważyć **respec** w zwykłym trybie.

## Istotne ograniczenia danych

- Drzewka w WARLOCK_SKILL_TREES.md pochodzą z **ChroniconDB 1.52.0**, a gramy w **1.61.x**. Dostępność, progi, wartości i połączenia mogą się różnić. **Screen użytkownika wygrywa**.
- Inspiracja community: [starter discussion — Blood Curse/Infection](https://www.reddit.com/r/Chronicon/comments/ifb6w2/), [Corruptor/Reaper AoE setup](https://www.reddit.com/r/Chronicon/comments/lwpmok/). To inspiracje, nie kopie pełnych endgame buildów.
- [SteamDB patch 1.60.1 (29.09.2026)](https://steamdb.info/patchnotes/25575785/) — ważne zmiany tagów Soul Skills i innych interakcji Warlocka.
- Każdy **potwierdzony** punkt zapisujemy natychmiast w WARLOCK_PROGRESS.md. Nie wpisywać rekomendacji jako decyzji wykonanej.
