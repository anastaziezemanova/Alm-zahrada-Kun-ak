# Almé Gardens — Design System

> **Almé** je studio pro návrh soukromých zahrad. Boutique studio v premium segmentu, Praha · est. 2026.
> Tento design system kodifikuje vizuální i verbální identitu značky a slouží zejména pro tvorbu **portfolií architektonických studií ve formátu A3**, dále pro web, prezentace a tištěné aplikace.

Brand holder: **Ing. Anastázie Zemanová**, krajinářská architektka · almegardens@gmail.com · almegardens.cz
Sídlo: Družstevní 343, Jindřichův Hradec II · IČO 17432898

---

## 1 · Company / product context

Almé je **butikové studio zahradní a krajinářské architektury**. Navrhuje soukromé rodinné zahrady na horní hranici českého trhu — mezi anonymními zahradními firmami a mezinárodními garden studii. Cílovou skupinou je vysokopříjmová klientela v ČR a Rakousku: majitelé rodinných domů, vil a víkendových sídel.

**Pozicování:** „Zahrada není ozdoba domu. Je to místo, kde dům končí a začíná svět.“
Studio se vědomě staví do polohy luxury značek typu **Aman, Aesop, Loro Piana, Vincent Van Duysen** — diskrétní luxus, ne okázalost.

**Pět hodnot značky:**
1. **Klid** — forma i komunikace; prostor smí dýchat.
2. **Důslednost** — detail, který nikdo nevidí, je často ten nejdůležitější.
3. **Trpělivost** — plánujeme na dekády, ne na sezónu.
4. **Vkus** — soudíme; když něco není dobré, řekneme to.
5. **Diskrétnost** — klienti nás nehledají, aby se chlubili.

### Surfaces / "products" represented
Almé nemá softwarový produkt. Identita žije na těchto plochách:
- **A3 portfolio / proposal** — hlavní deliverable tohoto design systemu (`slides/`).
- **Web** almegardens.cz — editorial, premium, Framer (`ui_kits/web/`).
- **Tištěné aplikace** — vizitka, dopisní papír, razítko/pečeť, Instagram grid (dokumentováno níže, šablony v `slides/` + `ui_kits/`).

### Source materials provided
- `uploads/Alme_Brand_Book.pdf` — 38 stran, kompletní průvodce značkou (identita, vizuál, aplikace, web).
- `uploads/Alme_Brand_Manual.pdf` — 25 stran, zhuštěná pravidla.
- `uploads/Alme_Logo_Prezentace.pdf` — obrazová prezentace loga (bez textu).
- 14 logo PNG variant (wordmark / descriptor / monogram / monogram-circle / seal / horizontal lockup × moss / on-moss / charcoal) → zkopírováno do `assets/logos/`.

*Reader nemusí mít k uploadům přístup — výše uvedené je manifest pro případ potřeby.*

---

## 2 · Content fundamentals — tone of voice

Almé mluví jako **kultivovaný, klidný odborník**, nikdy jako marketér. Pět principů hlasu:

1. **Mluvíme klidně.** Žádné vykřičníky, žádný emocionální nátlak. *„Pokud je věta dobrá, nepotřebuje vykřičník.“*
2. **Mluvíme krátce.** Jedna myšlenka v jedné větě. Premium klient čte rychle.
3. **Mluvíme konkrétně.** „Použili jsme habr, protože toleruje stín.“ — ne „vybíráme rostliny s ohledem na lokalitu“.
4. **Mluvíme vykáním.** Klient je vždy *vy*. Tykání je laciné. (I v Instagram bio.)
5. **Důslednost & ticho.** Mezera je nástroj. Raději vynechat než přidat.

**Casing:** Nadpisy se sázejí **větnou interpunkcí, ne Title Case** („Studie zahrady u Třeboně“). Eyebrows / štítky / nav jsou VERZÁLKY s prostrkáním. Wordmark je vždy `A L M É` (verzálky, tracking 0.22em).

**„My" vs „vy":** O studiu mluvíme v první osobě množného čísla („Navrhujeme…“, „Začínáme tam, kde končí váš dům“). Klienta oslovujeme vykáním („Napište nám.“).

**Emoji:** ❌ Nikdy. Žádné emoji, žádné smajlíky, žádné hashtagy v captionu (případně až do prvního komentáře).

### Co NEpoužíváme
- Klišé: „vaše zahrada snů“, „oáza klidu“, „kouzlo přírody“, „harmonie a sofistikovaná elegance“.
- Marketingové hyperboly: „výjimečný“, „revoluční“, „nezávazná konzultace ještě dnes!“.
- Anglicismy, kde čeština stačí.
- Familiárnost — klient není kamarád.
- **Bold v EB Garamondu** (používá se střídmě; raději italic nebo mezera).

### Příklady — NE → ANO
| ❌ NE (běžná zahradní firma) | ✅ ANO (Almé) |
|---|---|
| „Stvoříme pro vás zahradu vašich snů!“ | „Navrhneme zahradu, ve které budete chtít být.“ |
| „Naši zkušení architekti přinesou kouzlo přírody.“ | „Navrhujeme zahrady patnáct let. Začínáme tam, kde končí váš dům.“ |
| „Kontaktujte nás pro nezávaznou konzultaci ještě dnes!“ | „Napište nám. Ozveme se do dvou pracovních dní.“ |
| „Vytvoříme oázu klidu plnou harmonie.“ | „Místo, kde dům končí a krajina začíná.“ |

**Signature claims (lze používat jako hero/caption):**
„Slunce tu zapadá pomaleji.“ · „Statek se nestaví. Pokračuje.“ · „Z toho, co se nedá nakreslit.“
**Caption formát projektů:** `Studie · místo · rok` (např. `Studie · jižní Čechy · 2026`).

### Anti-charakter (čím Almé NENÍ → čím JE)
Hipsterské/hravé → **klidné, vážné, věcné** · Akademické/odtažité → **lidské, kompetentní** · Okázalý luxus → **diskrétní luxus** · Aktivistická ekologie → **profesionální zodpovědnost** · Sezónní/trendy → **nadčasové, trpělivé** · Familiární tykání → **klidné vykání**.

---

## 3 · Visual foundations

### Color
Identita stojí na **třech primárních barvách** a **maximálně třech barvách v jednom layoutu**. Tóny jsou tlumené, zemité, s hloubkou a klidem (inspirace Aman, Vincent Van Duysen).

**Primary trio:** Deep Moss Green `#2D3A2E` (akcent) · Charcoal `#1A1A1A` (text) · Warm Cream `#F5F1EA` (pozadí).
**Secondary trio:** Stone Gray `#8C8478` (popisky) · Aged Bronze `#8B7355` (teplý akcent) · Off-White `#FAF8F3` (zdvižená plocha).
**Extended light surfaces:** `#EDE7DA`, `#E5DFD0`, hairline `#DCD5C6`. Text: secondary `#4A4A45`, tertiary `#6A655B`.
**Dark variant:** ground `#1B2620`, surface `#23302A`, akcent **gold `#C9A77A`** (rezervováno pro tmavé plochy — pečetě, hero, OG snímky).

**Čemu se vyhnout:** Kelly green, acid lime, royal blue, fialová, vysoká saturace. Vše, co evokuje low-end zahradnictví.

### Typography
- **EB Garamond** (serif) — display, nadpisy, hero claim, citace, wordmark. Regular (400), výjimečně Medium (500), italic (400) pro citace. *Bold se používá střídmě.* Tisk 28–96 pt, web 40–96 px.
- **Inter** (sans) — body, navigace, popisky, tabulky, formuláře. Regular (400), důrazy Medium (500), malé nadpisy/štítky Semibold (600). Tisk 9–12 pt, web 14–18 px.
- **JetBrains Mono** — technické captiony, měřítka, souřadnice, štítky projektů (editorial-technický akcent vhodný pro A3 architektonické portfolio).

**Hierarchie — 7 úrovní** (max 3 velikosti na layout; raději mezera než větší písmo):
HERO 96 / H1 48–56 / H2 italic 28–34 / H3 (eyebrow) Inter Semibold caps / BODY Inter 16 / CAPTION mono 11 / QUOTE italic 16–22.

Wordmark = EB Garamond Regular, **tracking 0.22em**, verzálky.

### Spacing & layout
- **Vzdušnost je princip.** Hodně bílého (krémového) místa, štědré okraje. 8px base scale.
- A3 portfolio: okraje cca 18–25 mm, sloupcová sazba, jedna myšlenka na stranu.
- Layout je **editorial a pravoúhlý** — mřížka, hairline linky, žádné dekorativní rámečky.

### Backgrounds
- Plné plochy: **Warm Cream** (default) nebo **Deep Moss** / **dark `#1B2620`** pro kontrastní strany.
- **Fotografie full-bleed** je klíčový trust-signál (hero, OG, cover) — reálná fotka, **ne render**.
- Žádné gradienty pro dekoraci. Gradient se používá pouze jako **protection overlay** přes foto (tmavý spodní přechod) pro čitelnost textu na obraze.
- Žádné textury, vzory, hand-drawn ilustrace.

### Photography vibe
„Z toho, co se nedá nakreslit.“ Přirozené světlo, zlatá hodina, hloubka kompozice, **tlumené barvy**. Postprodukce: saturace −10–20 %, teplé tóny v shadows, neutrální highlights, mírně zvýšený kontrast. **Žádné Instagram filtry, žádné dramatické HDR.** Postava v zahradě jen z dálky — dojem prostoru, ne lidí. Čtyři typy záběrů: Wide / Medium / Detail / Top-down.

### Borders, radii, elevation
- **Radii ≈ 0.** Maximum `2px` (tlačítka, vstupní pole). Pill/kruh pouze pro monogram-seal.
- **Hairlines místo stínů.** Elevaci vyjadřujeme jemnou linkou (`#DCD5C6`) a mezerou, ne těžkým drop-shadow.
- Pokud je stín potřeba: `0 12px 32px -18px rgba(26,26,26,.18)` — měkký, sotva patrný.
- **Cards** = krémová/off-white plocha + 1px hairline, plochá, bez zaoblení. Žádné kartičky se zaoblenými rohy a barevným levým okrajem.

### Motion & states
- **Animace:** minimální, klidné. Jemné fade (200–400 ms), `ease`/`ease-out`. Žádné bounce, žádné dekorativní smyčky, žádné parallax cirkusy. Respektovat `prefers-reduced-motion`.
- **Hover:** jemné ztlumení (opacity ~0.7) nebo přechod barvy textu k moss; u tlačítek prohloubení pozadí. Žádné výrazné transformace.
- **Press:** lehké ztmavení barvy; bez „shrink" gimmicků.
- **Transparency / blur:** používat střídmě — protection gradient přes foto; jinak plné plochy.

### Logo system
Almé používá **wordmark, ne symbol** (symbol = signál pro mass market; wordmark = signál pro luxury). Šest variant: Primary Wordmark · Wordmark + Descriptor · Monogram · Monogram v kruhu · Pečeť/Seal · Horizontální lockup. Doporučená barva moss.
**Clear space** = 0.5× výška písmene. **Min. velikost:** digital 30 px, print 8 mm na výšku.
**Zákazy:** nedeformovat, nerotovat, neměnit barvu, nepřidávat stín/outline, neměnit prostrkání, nedávat na vzor ani na rušnou fotku.

---

## 4 · Iconography

Almé je **typografická značka, ne ikonografická.** V duchu luxury pozicování (wordmark, ne symbol) je ikonografie záměrně **minimální až žádná**.

- **Žádný icon font, žádný icon set.** Brand book ani manual nepředepisuje žádnou ikonovou knihovnu. Plochy se řeší typografií, mezerou a hairline linkami — ne piktogramy.
- **Žádné emoji, žádné unicode piktogramy** jako dekorace (viz tone of voice — emoji jsou zakázány).
- **Jediný „grafický" prvek je monogram „A"** (EB Garamond) a jeho varianta v kruhu / pečeti. Slouží jako značka, favicon, vodoznak a razítko — viz `assets/logos/`.
- **Funkční glyfy** (pokud jsou nezbytné v UI a portfoliu) se kreslí střídmě a v jednotném duchu:
  - **Šipka** `→` (a `←`) — sázená v **EB Garamond** jako součást textu CTA („Odeslat →"), ne jako tlačítková ikona.
  - **Oddělovač** `·` (middot) a **em-dash** `—` — typografické předěly v captionech a metadatech (`Studie · jižní Čechy · 2026`).
  - **Vertikální hairline `|`** v horizontálním lockupu odděluje monogram od wordmarku.
- **Pokud projekt nevyhnutelně potřebuje liniové ikony** (např. UI prvky webu — menu, jazyk, kontakt), použij **Lucide** z CDN (`https://unpkg.com/lucide@latest`) v **1.5px stroke**, barva moss/charcoal, bez výplně — je to nejbližší match k tenké, klidné, geometrické lince značky. **Toto je substituce — značka oficiálně žádný icon set nemá; používej jen tam, kde je to funkčně nutné, a nikdy dekorativně.** *(Flagged k odsouhlasení.)*

**Reálné assety v repu:** `assets/logos/` — 14 PNG (wordmark, descriptor, monogram, monogram-circle, seal, horizontal lockup; ve variantách moss / on-moss / charcoal). Žádné ilustrace ani background textury (značka je nepoužívá).

---

## 5 · Iconography assets summary
Viz `assets/logos/`. Nic dalšího — záměrně.

---



---

## 6 · Index / manifest

| Soubor / složka | Obsah |
|---|---|
| `README.md` | Tento dokument — kontext, tone of voice, vizuální foundations, ikonografie, index. |
| `SKILL.md` | Agent Skill manifest (cross-kompatibilní s Claude Code). |
| `colors_and_type.css` | CSS proměnné: barvy (light + dark), type scale, tracking, spacing, radii, stíny + sémantické třídy. **Importuj jako první.** |
| `assets/logos/` | 14 oficiálních logo PNG (wordmark / descriptor / monogram / circle / seal / lockup × moss / on-moss / charcoal). |
| `preview/` | 21 HTML karet pro Design System tab (Colors, Type, Spacing, Components, Brand). |
| `slides/` | **A3 portfolio šablony** (1480×1047): `index.html` (obsah), `cover`, `project-detail`, `photo-grid`, `quote`, `plan`, `contact` + `portfolio.css`. |
| `ui_kits/web/` | Recreation webu almegardens.cz (React+Babel): `index.html`, `components.jsx`, `pages.jsx`, `README.md`. |

### Jak začít
1. Importuj `colors_and_type.css`.
2. Pro **A3 portfolio**: zkopíruj šablonu ze `slides/`, vyměň obsah a nahraď fotky reálnými snímky.
3. Pro **web/UI**: čerpej z `ui_kits/web/` komponent.
4. Loga ber ze `assets/logos/` (preferuj moss wordmark).
5. Drž se tone of voice a barevných pravidel (max 3 barvy, žádné emoji).

### Fonty
EB Garamond · Inter · JetBrains Mono — všechny z **Google Fonts** (načítané přes `@import` v `colors_and_type.css`). Žádné lokální TTF nejsou potřeba; pro offline/print export je případně doplň do `fonts/`.
