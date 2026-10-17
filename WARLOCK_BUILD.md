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
| **RB** | **Soul Eater** (Reaper) | szybkie leczenie za **1 Soul**, w 1.52 ranga 1 przywraca 10% max HP | nie — awaryjny |
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

## Stan i najbliższy KONKRETNY następny punkt (18.10.2026)

**Potwierdzone 7 wydanych punktów, 0 wolnych:** Corruptor — Blood Curse 3, Epidemic 1, Infection 1, Flesh Rot 1; Lich — **Soul Warp 1**. **B = Soul Warp** (użytkownik potwierdził rzeczywiste przypisanie na padzie). Przypisania Blood Curse na RT i Flesh Rot na LT pozostają do potwierdzenia.

**Kolejny cel, gdy pojawi się punkt: Soul Eater 0 → 1 (Reaper)** — awaryjne leczenie za Soul na **RB**. Wartość 10% max HP za 1 duszę dotyczy starej wersji 1.52; próg i tooltip sprawdzić w 1.61. Nie wydawać ani nie uznawać za przypisany przed potwierdzeniem. Po leczeniu wracamy do gałęzi Corruptor i rozwoju Infection → Bursting Boils → Contagion/Outbreak i Poison Nova.

Dzięki temu mamy osobno zdolność ratunkowej ucieczki (**B**) i docelowe leczenie (**RB**), bez Auto Cast tych dwóch skilli.

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
