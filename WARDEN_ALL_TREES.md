# Warden — wszystkie drzewka i Mastery

Ten plik jest lokalną ściągą do prowadzenia naszego **Wardena-łucznika w Hardcore**. Ma pozwolić podejmować decyzje o kolejnych punktach bez ponownego szukania podstawowego układu w internecie.

## Jak liczymy „5 drzewek”

Warden ma cztery główne specjalizacje oraz osobną zakładkę Mastery:

1. **Wind Ranger** — Physical / Archery
2. **Druid** — Poison / Nature
3. **Storm Caller** — Lightning / Storm
4. **Winter Herald** — Frost
5. **Mastery** — rozwój przekrojowy wszystkich czterech specjalizacji

Dla naszej postaci najważniejszy jest **Wind Ranger**, ale build może brać wybrane defensywne i użytkowe punkty również z pozostałych drzewek.

## Zasada wersji

- Gramy na **Chronicon 1.61.x**.
- Publiczny pełny dump, który mamy jako bazę strukturalną, pochodzi z **ChroniconDB 1.52.0**.
- Aktualizacja 1.60.1 zmieniała część synergii Wardena, więc przy różnicy między repo a ekranem gry **screen 1.61 ma zawsze pierwszeństwo**.
- Nie zgadujemy połączeń. Jeśli nowe zdjęcie pokaże inną nazwę, pozycję, wymaganie albo wartość, poprawiamy ten plik.

---

# 1. Wind Ranger — Physical / Archery

To nasze główne drzewko.

## Potwierdzone i istotne elementy

| Skill | Rola | Znaczenie dla naszego buildu |
|---|---|---|
| **Rapid Shot** | podstawowy atak Archery | **RDZEŃ**, RT |
| **Tumble** | unik / mobilność | **HC RDZEŃ**, B |
| **Multi Shot** | wielostrzał | sytuacyjny |
| **Gale** | twistery / knockback | sytuacyjny |
| **Overdraw** | penetracja strzał / synergia Archery | **RDZEŃ** |
| **Arrow Hail** | obszarowy ostrzał | opcjonalny |
| **Splinter** | dodatkowy proc Physical | **RDZEŃ** |
| **Master Ranger** | duży buff Archery | później bardzo mocny |
| **Readiness** | Attack Speed | wysoki priorytet |
| **Double Draw** | dodatkowa strzała, on-hit | **RDZEŃ** |
| **Archer** | zwiększa obrażenia Archery | **RDZEŃ** |
| **Run With The Wind** | Movement Speed po evade | mocne w Hardcore |
| **Razor Tips** | Bleed z Splinter | **RDZEŃ** |
| **Seeds** | synergia Razor Tips z Druid/Pods | opcjonalna hybryda |
| **Wind Ranger** | pasywna linia specjalizacji | Physical + Attack/Movement Speed |

Pełniejsza lokalna notatka dla tej gałęzi jest również w `WIND_RANGER_SKILL_TREE.md`.

## Priorytet naszego buildu

**Rapid Shot → Archer 1 wcześnie → Splinter → Double Draw → Razor Tips → Overdraw**, a następnie rozwój Attack Speed, mobilności i defensywy.

---

# 2. Druid — Poison / Nature

Druid nie jest naszym głównym źródłem obrażeń, ale ma bardzo wartościową defensywę i sustain dla Hardcore.

## Znane elementy drzewka

| Skill | Rola | Znaczenie dla nas |
|---|---|---|
| **Poison Shot** | podstawowy Poison attack | zwykle pomijamy |
| **Agility** | Evasion | **bardzo dobre HC** |
| **Vine Shot** | pull / Poison DoT | opcjonalne |
| **Antivenom** | Poison Resistance / odporność na poison DoT | sytuacyjne |
| **Acid Rain** | AoE Poison | pomijamy w naszym buildzie |
| **Spores** | proc Poison | ważne dla buildów Druid |
| **Spiderlings** | companions | opcjonalne |
| **Bloom** | odzyskiwanie Health/Mana | bardzo dobre sustain, jeśli wchodzimy w tę gałąź |
| **Overgrowth** | Poison cooldown / wzmocnienie mushroomów | nie jest priorytetem |
| **Leaf Wind** | regeneracja życia | **HC bardzo wartościowe** |
| **Root Veil** | tarcza na bazie max Health | **HC bardzo wartościowe** |
| **Wild Growth** | wydłuża efekt powiązanego skilla | wsparcie defensywy |
| **Spore Wind** | Poison basic/atak stożkowy | nie dla głównego buildu |
| **Boom Shrooms** | AoE mushrooms | nie dla głównego buildu |
| **Pods** | proc / synergia Poison | ważne tylko przy hybrydzie z Seeds |
| **Barkskin** | Damage Reduction | **HC — jeśli dostępne po drodze, mocny kandydat** |

## Po co możemy tu wejść

Głównie po **Evasion, Root Veil, Leaf Wind, Damage Reduction i sustain**. Nie zmieniamy Wardena w Poison build tylko po to, żeby dojść do tych bonusów.

---

# 3. Storm Caller — Lightning / Storm

Najważniejsze drzewko wspierające nasz build po Wind Rangerze. Ma Evasion, ruch, kontrolę i defensywę.

## Znane elementy drzewka

| Skill | Rola | Znaczenie dla nas |
|---|---|---|
| **Charged Arrow** | podstawowy Lightning/Archery | nie jest naszym głównym atakiem |
| **Chain Lightning** | Lightning chain | opcjonalne |
| **Storm Caller** | linia specjalizacji | Lightning + Crit + Overpower |
| **Paralyze** | stun z Lightning critów | kontrola |
| **Pixies / Wisps** | companions | mogą odciągać uwagę / wspierać build |
| **Empowerment** | aura Damage | dobry support |
| **Eye of the Storm** | Evasion + Movement Speed + cooldown Storm/Nature | **HC wysoki priorytet** |
| **Thunder Storm** | obszarowy Lightning DoT | opcjonalne |
| **Storm Mender** | bardzo mocna defensywa / osłona | **HC bardzo ważne**, jeśli droga punktowa ma sens |
| **Sprint** | Movement Speed | **bardzo dobre HC** |
| **Agility / Acrobat synergie** | ruch i evade | dobre wsparcie |
| **Static** | proc Lightning | dla buildów Lightning |
| **Lightning Rod** | proc Lightning | dla buildów Lightning |
| **Taze** | kontrola | przydatne utility |
| **Squall** | synergia Storm | sytuacyjne |

## Po co możemy tu wejść

Dla naszego łucznika: **Evasion, Movement Speed, Sprint, Storm Mender, kontrola**. Nie inwestujemy w Lightning DPS bez konkretnego powodu.

---

# 4. Winter Herald — Frost

Drzewko z dużą ilością kontroli, spowolnień, companionów i defensywy.

## Znane elementy drzewka

| Skill | Rola | Znaczenie dla nas |
|---|---|---|
| **Frost Arrow** | podstawowy Frost/Archery | nie jest naszym głównym atakiem |
| **Guide** | Companion Health | tylko przy companionach |
| **Winter Storm** | Frost AoE | opcjonalne |
| **Frost Bomb** | Frost basic/AoE | opcjonalne |
| **Winter's Chill** | Chill / slow | **dobre bezpieczeństwo** |
| **Biting Cold** | Crit aura | potencjalny support |
| **Hail** | dodatkowy proc Frost | głównie Frost build |
| **Hail Storm** | AoE Frost | głównie Frost build |
| **Snow Blast** | proc AoE Frost | synergie endgame |
| **Pelted** | proc/DoT synergia Hail | nie dla podstawowego łucznika |
| **Pummel** | wzmacnia Pelted | nie dla podstawowego łucznika |
| **Air Freeze** | Frost active / burst-control | opcjonalne |
| **Torrent** | synergia cooldown/proc | opcjonalne |
| **Winter** | buff Frost | nie jest priorytetem |
| **Wolfpack / Wolves** | companions | mogą tankować i odciągać aggro |
| **Winter Breeze** | Chill przy kontakcie/evade | dobre HC |
| **Ice Dash** | Movement Speed po evade | dobre HC |
| **Winterbringer** | ultimate / Evasion + resist support | mocny defensywnie |

## Po co możemy tu wejść

Przede wszystkim po **kontrolę, chill, Evasion/resisty i ewentualnie wilki jako żywe tarcze**. Punkty damage Frost są dla naszego buildu drugorzędne.

---

# 5. Mastery

Mastery jest piątą zakładką, ale nie jest piątą specjalizacją elementarną. Działa przekrojowo na wszystkie cztery drzewka.

## Główne linie

- **Wind Ranger Mastery**
- **Druid Mastery**
- **Storm Caller Mastery**
- **Winter Herald Mastery**
- Class Mastery I / II / III

## Ważne mastery dla naszego łucznika

| Mastery | Efekt / kierunek | Priorytet |
|---|---|---|
| **Assault** | Attack Speed | wysoki |
| **Swift Winds** | Movement Speed | wysoki HC |
| **Storm Reflex** | Evasion | wysoki HC |
| **Frost Shell** | Damage Reduction | bardzo wysoki HC |
| **Immunity** | All Resistances | wysoki HC |
| **Triple Draw** | dodatkowa strzała z Double Draw | **bardzo wysoki DPS** |
| **Fragmentations** | proc Splinter | **wysoki** |
| **Razor Cuts** | zwiększa Splinter | **wysoki** |
| **Precision** | zwiększa Double Draw | **wysoki** |
| **Careful Aim** | Archery damage podczas stania | sytuacyjne; w HC nie stoimy na siłę |
| **Wind Runner** | bonus podczas ruchu | naturalnie pasuje do HC |
| **Momentum** | Tumble/Escape/Trapflip uruchamia Sprint | **bardzo mocna mobilność** |
| **Restorative Roots** | Root Veil uruchamia Leaf Wind | dobry defensywny pakiet |
| **Acrobat** | wzmacnia Agility i Sprint | wysoki HC, jeśli inwestujemy w te skille |
| **Mega Wisp** | scala Wispy | tylko przy companion Lightning |
| **Whirling Snow** | Snow Blast daje Evasion | tylko przy Frost synergiach |
| **Splinter Arrows** | zwiększa Double Draw i Splinter | **rdzeń** |
| **Natural Harmony** | Spores / Pods | tylko Druid/hybryda |
| **Static Rods** | Static / Lightning Rod | tylko Lightning |
| **Charged Wisps** | Wisp | tylko companion Lightning |
| **Hailblast** | Snow Blast / Hail | tylko Frost |
| **Wide Synergy** | obrażenia wielu elementów | niższy priorytet w czystym Physical |
| **Wind Ranger Focus** | damage Wind Ranger | wysoki |
| **Druid Focus** | damage Druid | niski dla nas |
| **Storm Caller Focus** | damage Storm Caller | niski dla nas |
| **Winter Herald Focus** | damage Winter Herald | niski dla nas |

## Mastery — kolejność dla naszego buildu

Najpierw wzmacniamy mechanikę **Wind Ranger / Rapid Shot / Splinter / Double Draw**, potem **Attack Speed**, następnie defensywę Hardcore: **Evasion, Damage Reduction, Movement Speed, Resistances**. Pozostałe mastery bierzemy tylko wtedy, gdy faktycznie używamy mechaniki, którą wzmacniają.

---

# Jak korzystamy z tego pliku przy każdym punkcie

Przed każdą decyzją sprawdzamy:

1. `WARDEN_PROGRESS.md` — co faktycznie mamy.
2. `WARDEN_ALL_TREES.md` — jakie opcje istnieją również poza Wind Rangerem.
3. `WIND_RANGER_SKILL_TREE.md` — szczegóły głównej gałęzi.
4. `WARDEN_HARDCORE_ARCHER.md` — docelowy plan buildu i sprzętu.

Dopiero potem wskazujemy **jeden konkretny następny punkt**.

# Co aktualizujemy ze screenów 1.61

Dla każdego drzewka dopisujemy, gdy tylko pojawi się na screenie:

- dokładny rząd / próg,
- pozycję i połączenia między skillami,
- maksymalną liczbę rang,
- aktualne wartości tooltipów,
- wymaganą liczbę punktów do otwarcia następnego poziomu,
- informację, czy skill jest obowiązkowy, opcjonalny czy pomijany dla naszego builda.

W ten sposób repo jest źródłem roboczym dla naszej konkretnej postaci, a internet służy tylko do uzupełniania nowych lub zmienionych elementów.