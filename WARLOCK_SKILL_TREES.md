# Warlock (czarnoksiężnik) — komplet katalogu czterech drzewek i Mastery

**Stan opracowania:** 17.10.2026. **Gra użytkownika:** Chronicon 1.61.x. **Źródło geometrii:** [ChroniconDB — dane 1.52.0](https://github.com/gabriel-dehan/chronicondb-client/blob/main/src/engine/data/1.52.0/sources/skilldata_1.52.0.json). Dump jest starszy od wersji gracza: **dokładne progi, nazwy i wartości w 1.61 potwierdzamy screenami**. Nie wydajemy punktów na podstawie samego starego układu.

## Status weryfikacji wersji 1.61 (20.10.2026)

- **POTWIERDZONE W 1.61** — tylko informacje odczytane bezpośrednio z ekranu gry lub wyraźnie potwierdzone przez gracza; zapisujemy źródło i datę potwierdzenia.
- **DO WERYFIKACJI — ŹRÓDŁO 1.52 / ARCHIWALNE** — wszystkie pozostałe nazwy, efekty, wartości, rangi, wymagania i układ pól pochodzące ze starszych eksportów. Nie traktować ich jako potwierdzonych dla 1.61.
- **ROZBIEŻNOŚĆ** — gdy opis z gry różni się od archiwum, obowiązuje aktualny tooltip gry. Przykład: Bursting Boils, pierwsza ranga — 10% na ekranie 1.61 wobec 12% w starszych danych (zgłoszona różnica; do ponownego sprawdzenia na ekranie, jeśli będzie istotna dla decyzji).
- Samo posiadanie punktów w umiejętności **nie potwierdza** wszystkich liczb i efektów z archiwalnego opisu. Wpisy w tabelach poniżej domyślnie mają status **DO WERYFIKACJI**, chyba że konkretny parametr opisano osobno jako potwierdzony.

## Specjalizacje

- **Corruptor** — Poison, Infection, klątwy, towarzysze.
- **Lich** — Frost, Soul Warp, ochrona i kontrola tłumu.
- **Demonologist** — Fire, eksplozje, demony, obrona.
- **Reaper** — Shadow, dusze, leczenie, bariery.
- **Mastery** — osobna piąta zakładka, nie odrębny żywioł.

## Legenda geometrii

Kolumna **X** (2–9) i wiersz **Y** (0–6) to pozycja pola w drzewku 1.52, nie wymagany poziom postaci. **Rangi** oznaczają maksymalną liczbę punktów w 1.52. **Zależność** to wymagany skill, a nie pełny próg otwarcia kolumny. Kilka skilli o jednakowych X/Y może być wariantami tego samego pola. Pasywki działają bez przypisania przycisku; rytuały i towarzysze mają własne zasady aktywacji.

## Corruptor — pełny indeks (39 skilli)

| Umiejętność | Typ | X/Y | Rangi | Zależność | Przydatność/efekt (wybrane) |
|---|---|---:|---:|---|---|
| Corruptor | pasywny | 0/3 | 89 | — | — |
| Epidemic | pasywny | 2/0 | 5 | — | Attack Speed |
| Soul Bane | aktywny | 2/1 | 1 | — | — |
| Soul Curse | aktywny | 2/1 | 1 | — | — |
| Soul Sorcery | aktywny | 2/1 | 1 | — | — |
| Blood Curse | aktywny | 2/3 | 5 | — | Podstawowy AoE: trucizna od razu i w czasie |
| Poison Bolt | aktywny | 2/3 | 5 | — | — |
| Summoner | pasywny | 2/5 | 5 | — | — |
| Master of the Arts | pasywny | 3/1 | 3 | Soul Bane / Soul Curse / Soul Sorcery | — |
| Flesh Rot | aktywny | 3/2 | 5 | — | Rozprzestrzeniająca się klątwa DoT |
| Plague | aktywny | 3/2 | 5 | — | Chmura trucizny wokół Warlocka |
| Poison Skull | aktywny | 3/2 | 5 | — | — |
| Infection | pasywny | 3/6 | 3 | — | Poison skille nakładają DoT |
| Tainted Blood | pasywny | 4/0 | 3 | Epidemic | — |
| Misery | pasywny | 4/1 | 3 | Poison Skull / Plague / Flesh Rot | — |
| Plague Bearer | towarzysz | 4/3 | 5 | — | Towarzysze z dystansowym Poison Bolt |
| Zombie | towarzysz | 4/3 | 5 | — | Tankujące przywołańce Poison |
| Bursting Boils | pasywny | 4/5 | 3 | Infection | Eksplozja Infection po trafieniach Poison |
| Widespread Disease | pasywny | 5/1 | 3 | Misery | — |
| Bane of the Dead | aktywny | 5/2 | 5 | — | — |
| Mind Torture | aktywny | 5/2 | 5 | — | — |
| Poison Nova | aktywny | 5/2 | 5 | — | Nova trucizny wokół postaci |
| Pestilence | pasywny | 5/3 | 3 | Zombie / Plague Bearer | — |
| Contagion | pasywny | 5/4 | 3 | Bursting Boils | Rozprzestrzenianie Infection |
| Toxic Veil | pasywny | 6/0 | 3 | Tainted Blood | Evasion |
| Sickly Fatigue | pasywny | 6/2 | 3 | Poison Nova / Bane of the Dead / Mind Torture | — |
| Outbreak | pasywny | 6/5 | 3 | Bursting Boils | Eksplozja zakażonych po śmierci |
| Rapid Spread | pasywny | 7/1 | 3 | Sickly Fatigue | — |
| Horde | pasywny | 7/3 | 3 | Pestilence | — |
| Soul Toxin | pasywny | 7/5 | 3 | Outbreak | — |
| Living Blood | pasywny | 7/6 | 3 | Infection | — |
| Soul Power | pasywny | 8/0 | 3 | Vile Pool / Affliction / Corruption | — |
| Affliction | aktywny | 8/1 | 5 | — | — |
| Corruption | aktywny | 8/1 | 5 | — | — |
| Vile Pool | aktywny | 8/1 | 5 | — | — |
| Fueled By Disease | pasywny | 8/3 | 3 | Vile Pool / Affliction / Corruption | — |
| Cloak of Infection | ultimate | 9/3 | 1 | — | — |
| Plague Lord | ultimate | 9/3 | 1 | — | — |
| Infected Spirits | pasywny | 9/5 | 1 | Soul Toxin | — |

## Lich — pełny indeks (40 skilli)

| Umiejętność | Typ | X/Y | Rangi | Zależność | Przydatność/efekt (wybrane) |
|---|---|---:|---:|---|---|
| Lich | pasywny | 0/3 | 92 | — | — |
| Death Shroud | aktywny | 2/0 | 1 | — | — |
| Soul Warp | aktywny | 2/0 | 1 | — | Teleport, może zużywać dusze |
| Shattering Ice | pasywny | 2/1 | 5 | — | — |
| Frost Spear | aktywny | 2/3 | 5 | — | — |
| Frozen Flesh | aktywny | 2/3 | 5 | — | — |
| Deep Pools | pasywny | 2/5 | 5 | — | — |
| Flicker | pasywny | 3/0 | 3 | Soul Warp / Death Shroud | Evasion po teleportacji |
| Ruin | aktywny | 3/4 | 5 | — | — |
| Serrated Spears | aktywny | 3/4 | 5 | — | — |
| Skull Bomb | aktywny | 3/4 | 5 | — | — |
| Bone Chill | pasywny | 3/6 | 3 | — | — |
| Soul Thief | pasywny | 4/0 | 3 | Flicker | — |
| Ritual of Perforation | rytuał | 4/2 | 5 | — | — |
| Ritual of Summoning | rytuał | 4/2 | 5 | — | — |
| Ritual of Tongues | rytuał | 4/2 | 5 | — | — |
| Quick Freeze | pasywny | 4/4 | 3 | Serrated Spears / Skull Bomb / Ruin | — |
| Cold Death | pasywny | 4/5 | 3 | Bone Chill | — |
| Chant | pasywny | 5/1 | 3 | Ritual of Perforation / Ritual of Tongues / Ritual of Summoning | — |
| Ritualistic Sorcery | pasywny | 5/2 | 3 | Ritual of Perforation / Ritual of Tongues / Ritual of Summoning | — |
| Frigid Star | aktywny | 5/3 | 5 | — | — |
| Frost Nova | aktywny | 5/3 | 5 | — | — |
| Frozen Fate | aktywny | 5/3 | 5 | — | — |
| Frozen Veil | pasywny | 5/6 | 3 | — | Bariera przy zbieraniu dusz |
| Frozen Core | pasywny | 6/1 | 3 | — | — |
| Brittle Bones | pasywny | 6/3 | 3 | Frigid Star / Frost Nova / Frozen Fate | — |
| Frost Hand | pasywny | 6/4 | 3 | Quick Freeze | — |
| Death's Breath | pasywny | 6/6 | 3 | Frozen Veil | — |
| Coldhearted | pasywny | 7/0 | 3 | Frozen Core | — |
| Doublecast | pasywny | 7/3 | 3 | Brittle Bones | — |
| Corpse Shatter | pasywny | 7/5 | 3 | Cold Death | — |
| Spirit of Torment | pasywny | 7/6 | 3 | Death's Breath | — |
| Cold Embrace | pasywny | 8/0 | 3 | Comet / Deathly Barrage / Curse of Doom | — |
| Comet | aktywny | 8/1 | 5 | — | — |
| Curse of Doom | aktywny | 8/1 | 5 | — | — |
| Deathly Barrage | aktywny | 8/1 | 5 | — | — |
| Anguish | pasywny | 8/2 | 3 | Comet / Deathly Barrage / Curse of Doom | — |
| Frozen Death | ultimate | 9/3 | 1 | — | — |
| Lich Power | ultimate | 9/3 | 1 | — | — |
| Corpse Combustion | pasywny | 9/5 | 1 | Corpse Shatter | — |

## Demonologist — pełny indeks (38 skilli)

| Umiejętność | Typ | X/Y | Rangi | Zależność | Przydatność/efekt (wybrane) |
|---|---|---:|---:|---|---|
| Demonologist | pasywny | 0/3 | 85 | — | — |
| Demon Skin | pasywny | 2/0 | 3 | — | Damage Reduction |
| Blood Rite | aktywny | 2/1 | 3 | — | — |
| Soul Trap | aktywny | 2/1 | 3 | — | Zdobywanie dusz kosztem Health |
| Firebomb | aktywny | 2/3 | 5 | — | — |
| Flashfire | aktywny | 2/3 | 5 | — | Szybki atak Fire, alternatywny RT |
| Demon Heart | pasywny | 2/5 | 5 | — | — |
| Thirsty Souls | pasywny | 3/1 | 3 | Soul Trap / Blood Rite | — |
| Detonation | aktywny | 3/2 | 5 | — | Ogień AoE i odrzut |
| Heat Wave | aktywny | 3/2 | 5 | — | — |
| Hell Pit | aktywny | 3/2 | 5 | — | — |
| Flaming Hells | pasywny | 3/6 | 3 | — | — |
| Demonic Fury | pasywny | 4/0 | 3 | Demon Skin | — |
| Torment | pasywny | 4/2 | 3 | Detonation / Hell Pit / Heat Wave | — |
| Imps | towarzysz | 4/4 | 5 | — | — |
| Little Devils | towarzysz | 4/4 | 5 | — | — |
| Eternal Flames | pasywny | 4/5 | 3 | Flaming Hells | — |
| Fire Nova | aktywny | 5/1 | 5 | — | — |
| Hellfire | aktywny | 5/1 | 5 | — | — |
| Wall of Fire | aktywny | 5/1 | 5 | — | — |
| Soul Empowerment | pasywny | 5/3 | 3 | — | — |
| Volatile | pasywny | 5/4 | 1 | Imps / Little Devils | — |
| Combustion | pasywny | 5/6 | 3 | Flaming Hells | — |
| Devastation | pasywny | 6/0 | 3 | Hellfire / Fire Nova / Wall of Fire | — |
| Burning Attunement | pasywny | 6/2 | 3 | Torment | — |
| Fiery Soul | pasywny | 6/5 | 1 | Combustion | — |
| Living Flames | pasywny | 7/0 | 3 | Devastation | — |
| Demonic Strength | pasywny | 7/4 | 3 | Volatile | — |
| Eruption | pasywny | 7/6 | 3 | Combustion | — |
| Armageddon | pasywny | 8/0 | 3 | Hell Caller | — |
| Hell Caller | pasywny | 8/1 | 3 | Meteor / Inferno / Fire Storm | — |
| Fire Storm | aktywny | 8/2 | 5 | — | Ogień AoE wokół postaci |
| Inferno | aktywny | 8/2 | 5 | — | — |
| Meteor | aktywny | 8/2 | 5 | — | — |
| Demonic Appetite | pasywny | 8/3 | 3 | Soul Empowerment | — |
| Demon Spawn | ultimate | 9/3 | 1 | — | — |
| Infernal Demon | ultimate | 9/3 | 1 | — | — |
| Death and Destruction | pasywny | 9/6 | 1 | Eruption | — |

## Reaper — pełny indeks (39 skilli)

| Umiejętność | Typ | X/Y | Rangi | Zależność | Przydatność/efekt (wybrane) |
|---|---|---:|---:|---|---|
| Reaper | pasywny | 0/3 | 87 | — | — |
| Undeath | pasywny | 2/0 | 3 | — | Maximum Health |
| Soul Barrier | aktywny | 2/1 | 3 | — | Tarcza kosztem dusz |
| Soul Eater | aktywny | 2/1 | 3 | — | Leczenie kosztem duszy |
| Hand of Death | aktywny | 2/3 | 5 | — | — |
| Screaming Skull | aktywny | 2/3 | 5 | — | — |
| The Dark Side | pasywny | 2/5 | 5 | — | — |
| Vampirism | pasywny | 3/0 | 3 | Undeath | Health on Hit |
| Curse of Woe | aktywny | 3/2 | 5 | — | — |
| Grave Blast | aktywny | 3/2 | 5 | — | — |
| Life Reap | aktywny | 3/2 | 5 | — | — |
| Masochism | pasywny | 3/6 | 3 | — | — |
| Endless Thirst | pasywny | 4/1 | 3 | Soul Eater / Soul Barrier | — |
| Weakened Soul | pasywny | 4/2 | 3 | Life Reap / Curse of Woe / Grave Blast | — |
| Ritual of Banes | rytuał | 4/4 | 5 | — | — |
| Ritual of Necromancy | rytuał | 4/4 | 5 | — | — |
| Ritual of Souls | rytuał | 4/4 | 5 | — | Bony za trzymane dusze |
| Soul Rip | pasywny | 4/5 | 3 | The Dark Side | — |
| Soul Feast | pasywny | 5/0 | 3 | Vampirism | Heal/Mana przy zebraniu duszy |
| Soul Reaper | pasywny | 5/1 | 3 | Weakened Soul | — |
| Bone Spears | aktywny | 5/3 | 5 | — | — |
| Curse of Reckoning | aktywny | 5/3 | 5 | — | — |
| Curse of Terror | aktywny | 5/3 | 5 | — | — |
| Dark Pleasure | pasywny | 5/6 | 3 | Masochism | — |
| Shadow Armor | pasywny | 6/0 | 3 | Soul Feast | — |
| Relish In Their Pain | pasywny | 6/2 | 3 | Curse of Reckoning / Curse of Terror / Bone Spears | — |
| Collector | pasywny | 6/4 | 3 | Ritual of Banes / Ritual of Souls / ID 730 / Ritual of Necromancy | — |
| Desecration | pasywny | 6/5 | 3 | Soul Rip | — |
| Sudden Death | pasywny | 7/0 | 3 | — | — |
| Death's Reach | pasywny | 7/2 | 3 | Relish In Their Pain | — |
| Dark Souls | pasywny | 7/6 | 1 | Dark Pleasure | — |
| Exoskeleton | pasywny | 8/1 | 3 | Bone Splinters | — |
| Bone Splinters | pasywny | 8/2 | 3 | Bone Storm / Bone Scythe / Bone Curse | — |
| Bone Curse | aktywny | 8/3 | 5 | — | — |
| Bone Scythe | aktywny | 8/3 | 5 | — | — |
| Bone Storm | aktywny | 8/3 | 5 | — | Wokół postaci Shadow DoT |
| Necrosis | pasywny | 9/0 | 1 | Sudden Death | — |
| Death Knight | ultimate | 9/4 | 1 | — | — |
| Vampire Lord | ultimate | 9/4 | 1 | — | — |

## Mastery — osobny atlas siedmiu wierszy

**Komplet archiwalnej mapy dostępnych wyborów i pola po polu jest w [WARLOCK_MASTERY_TREE.md](WARLOCK_MASTERY_TREE.md).** Osobny, maszynowo czytelny [WARLOCK_MASTERY_OPTIONS.json](WARLOCK_MASTERY_OPTIONS.json) zawiera 7 wierszy × 9 pól, pełne nazwy i identyfikatory 144 pierwotnych wariantów oraz skopiowane opcje wspólne w pozostałych wierszach.

**Istotna niezgodność wersji:** w 1.61 użytkownik widzi **5 ikon pierwszego pola R1-K1 Corruptora**; starszy eksport ma tylko **4** możliwości. Dlatego wykaz jest referencyjny, a konkretna premia i jej wartość wymagają potwierdzenia tooltipem przed wydaniem Mastery Point.

**Stan postaci na 18.10.2026:** Lv. 10 / M1; **1 wolny Mastery Point**, żaden wybór Mastery nie został jeszcze potwierdzony jako wykonany. Historia i punkty: [WARLOCK_PROGRESS.md](WARLOCK_PROGRESS.md).

## Aktualizacja pod 1.61

Po przesłaniu screenów uzupełniamy rzeczywiste połączenia, progi, maksymalne rangi i wartości tooltipów. Ekran z gry ma pierwszeństwo nad starszą bazą. Do decyzji sprawdzamy także WARLOCK_BUILD.md i WARLOCK_PROGRESS.md.
