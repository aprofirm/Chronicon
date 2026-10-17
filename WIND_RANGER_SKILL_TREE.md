# Warden — Wind Ranger / łucznik — lokalne drzewko

Ten plik jest lokalną ściągą do prowadzenia naszego **Wardena-łucznika w Hardcore**. Przy zwykłym rozdawaniu punktów korzystamy najpierw z repo, bez ponownego szukania układu w internecie.

## Ważne o wersji

- Aktualna rozgrywka: **Chronicon 1.61.x — 17.10.2026**.
- Publiczne dane strukturalne, które udało się zweryfikować, kończą się na **ChroniconDB 1.52.0**.
- **Screen z aktualnej gry ma zawsze pierwszeństwo** przed starszymi danymi.
- Nazwy, połączenia, progi i wartości, które zmieniły się w 1.61, poprawiamy tutaj na podstawie naszych screenów.

## Aktualny stan naszej postaci

**Poziom:** 3  
**Wolne punkty:** 0

| Skill | Punkty | Rola |
|---|---:|---|
| **Rapid Shot** | 1 | główny atak, **RT** |
| **Tumble** | 1 | unik / mobilność, **B** |
| **Archer** | 1 | pasywne zwiększenie obrażeń Archery |

Łącznie wydane: **3 punkty**.

---

# Katalog Wind Ranger

Poniżej zapisujemy mechanikę całej znanej gałęzi łucznika. Jeżeli na naszym ekranie 1.61 nazwa lub działanie któregoś pola jest inne, screen z gry nadpisuje ten opis.

| Skill | Typ | Co robi | Znaczenie dla naszego buildu |
|---|---|---|---|
| **Rapid Shot** | aktywny, Physical / Archery | Szybki podstawowy ostrzał z łuku; może zastępować normalny atak. | **RDZEŃ** — główny atak. |
| **Tumble** | aktywny, mobilność | Odskok / przewrót do tyłu służący do zmiany pozycji i uniku. | **HC RDZEŃ** — przycisk ratunkowy. |
| **Multi Shot** | aktywny, Physical / Archery | Wystrzeliwuje kilka strzał w szerokim stożku. | Sytuacyjny; nie jest podstawą naszego Rapid Shot/Bleed. |
| **Charged Arrow** | aktywny, Archery | Ładowany strzał łuczniczy. Dokładne aktualne wartości 1.61 sprawdzamy w UI, jeśli będzie nam potrzebny. | Opcjonalny. |
| **Master Ranger** | buff / duża pasywno-aktywna synergia | Zwiększa bazowe obrażenia Archery, zmniejsza ich bazowy cooldown i podnosi Attack Speed przez określony czas. | Mocny później; **sprawdzić aktualną nazwę w 1.61**, bo poradniki mogą używać starszego nazewnictwa. |
| **Mobility** | pasywka | Zwiększa Movement Speed podczas używania/castowania skilli Archery. | Bardzo dobra w Hardcore. |
| **Overdraw** | proc Archery | Atak Archery może uruchomić bez kosztu poprzednio użyty skill Archery w linii na celu. | **RDZEŃ**. |
| **Double Draw** | proc Archery | Skill Archery może wystrzelić dodatkową strzałę w tym samym kierunku; dodatkowa strzała może uruchamiać efekty on-hit. | **RDZEŃ**. |
| **Archer** | pasywka, 5 rang | Zwiększa obrażenia skilli **Archery**. Na naszym screenie: przy 0/5 tooltip pokazuje **+7%**, a przy maksymalnej randze **+15%**. | **RDZEŃ**; mamy obecnie 1 punkt. |
| **Distant Winds** | pasywka | Wzmacnia efekt związany z dystansem i zwiększa zasięg skilli Archery. | Drugorzędny / do oceny później. |
| **Splinters** | proc Physical | Fizyczne trafienia mogą tworzyć odłamki z trafionych wrogów; odłamki zadają Physical Damage, korzystają z efektów on-hit i dziedziczą crit po ataku wyzwalającym. | **RDZEŃ**. |
| **Razor Tips** | proc / Bleed | Splinters nakłada Bleed; obrażenia krwawienia skalują się z obrażeniami Splinters, a kolejne trafienia odświeżają czas. | **RDZEŃ** naszego Bleed. |
| **Feast** | sustain / obrona | Fizyczne trafienia krytyczne mogą przywracać procent maksymalnego życia. | **HC — bardzo wartościowe**. |
| **The Best Defense** | obrona | Podczas atakowania skillami Physical daje Damage Reduction. | **HC — wysoki priorytet**, jeśli dostępne w aktualnym układzie. |
| **Bottled Up Impatience** | pasywka | Gdy Elegant Execution jest gotowe, zapewnia Attack Speed. | Późniejsza synergia. |
| **Elegant Execution** | proc / crit | Co pewien czas następne trafienie Physical jest gwarantowanym critem i dostaje zwiększony Critical Damage. | Później; nie jest potrzebne na samym starcie. |

---

# Priorytety naszego buildu

## Rdzeń obrażeń

1. **Rapid Shot**
2. **Archer** — 1 punkt wcześnie, nie maksujemy od razu
3. **Splinters**
4. **Double Draw**
5. **Razor Tips**
6. **Overdraw**

## Bezpieczeństwo Hardcore

- **Tumble**
- **Mobility**
- **Feast**
- **The Best Defense**
- później inne źródła Evasion / Damage Reduction / sustain z pozostałych drzewek

## Drugorzędne / sytuacyjne

- Multi Shot
- Charged Arrow
- Distant Winds
- Bottled Up Impatience
- Elegant Execution
- Master Ranger — mocny później, ale nazwę i pozycję potwierdzamy na aktualnym ekranie 1.61

---

# Układ i połączenia w drzewku 1.61

Nie zapisujemy na siłę starej geometrii jako pewnika. Publiczny dump danych, który mamy, jest starszy niż nasza wersja gry, a **dokładne połączenia i pozycje w aktualnym 1.61 będziemy utrwalać z naszych screenów**.

Pierwszy potwierdzony punkt odniesienia z aktualnej gry:

- wybrane drzewko: **Wind Ranger**,
- Lv 3,
- Rapid Shot 1,
- Tumble 1,
- Archer 1,
- 0 wolnych punktów.

Gdy dostaniemy kolejny pełny screen drzewa, dopisujemy:

- rząd / próg każdego pola,
- maksymalną liczbę rang,
- bezpośrednie połączenia między polami,
- wymagania punktowe do kolejnych rzędów,
- aktualne wartości tooltipów z wersji 1.61.

W ten sposób po kilku awansach ten plik stanie się **dokładną mapą naszej aktualnej wersji gry**, a nie kopią starego drzewa z internetu.

---

# Procedura przy każdym awansie

Zanim powiem, gdzie wydać punkt, sprawdzam w tej kolejności:

1. `WARDEN_PROGRESS.md` — **co faktycznie mamy teraz**.
2. `WIND_RANGER_SKILL_TREE.md` — **lokalna mapa i mechanika skilli**.
3. `WARDEN_HARDCORE_ARCHER.md` — **docelowy plan buildu**.
4. Dopiero wtedy wskazuję konkretnie: **nazwa skilla + liczba punktów do wydania teraz**.

Internet jest potrzebny tylko wtedy, gdy trafimy na nowy skill / zmianę wersji, której jeszcze nie ma w repo.

---

# Źródło bazowe do weryfikacji

- nasze screeny z aktualnej gry — źródło nadrzędne,
- ChroniconDB, dane 1.52.0 — pomocnicza baza nazw i mechanik.

**Zasada:** nie zgadujemy. Jeśli screen 1.61 różni się od tego pliku, poprawiamy repo według gry.