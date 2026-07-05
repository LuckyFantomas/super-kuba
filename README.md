# Super Kuba 🍄

Mario-style skákačka o **50 levelech** s menu, výběrem levelů, obchodem (skiny + upgrady) a ukládáním postupu. Jeden HTML soubor bez závislostí — otevřeš dvojklikem, funguje na PC i mobilu.

🌐 **Hrát online:** **https://superkuba.vercel.app** (Vercel) · záloha: https://luckyfantomas.github.io/super-kuba/ (GitHub Pages)

## Ovládání
- **◀ ▶** (šipky nebo `A`/`D`) — chůze
- **mezerník / ↑ / `W`** — skok
  - **zmáčkni 2× = dvojskok** (druhý skok ve vzduchu)
  - **drž = skáčeš pořád dokola** (auto-skok ze země)
- Na mobilu jsou dole dotyková tlačítka
- **⌨️ Menu klávesnicí** — v menu, obchodě, výběru levelů, módech i nastavení se dá pohybovat **šipkami** (nahoru/dolů/vlevo/vpravo přepínají tlačítka) a potvrdit **Enter/mezerníkem** — nemusíš sahat po myši.

## Hudba
🎵 **Chiptune hudba na pozadí** — jednoduchá 8-bit smyčka. Zapíná/vypíná se tlačítkem **🎵 Hudba: zap/vyp** dole v hlavním menu (nastavení se ukládá). Spustí se po prvním kliknutí/klávese (prohlížeče blokují zvuk před interakcí).

## Přihlášení (přezdívka)
🎮 Při **prvním spuštění** hra vyzve hráče, ať zadá **přezdívku** (ne pravé jméno — nick do hry). Uloží se a objevuje se jako pozdrav v menu („Ahoj, {nick}!") a na sdíleném obrázku výsledku. Přezdívka se dá kdykoli změnit v **Nastavení**.

## ⚙️ Nastavení
Tlačítko **⚙️ Nastavení** v menu:
- **Jazyk / Language** — přepínač 🇨🇿 **Čeština** / 🇬🇧 **English**. Přepne celé UI (menu, obchod, trofeje, módy, zprávy) okamžitě a uloží se.
- **Přezdívka** — změna nicku.

## Herní mechaniky
- 👟 **Zašlápni nepřátele** shora (ze strany ti uberou život). Pronásledují tě a s levely jsou rychlejší.
- Od vyšších levelů potkáš i **speciální nepřátele:** 🐸 **Žabák** (poskakuje, od L7), 🔫 **Střelec** (pálí projektily, od L11) a 🛡️ **Tank** (velký, snese 2 zásahy, od L15).
- 🚧 **Brána (silové pole):** neprojdeš dál, dokud nezabiješ všechny Goomby před ní. U brány je 🔒 a počet zbývajících.
- ❓ **Lucky bloky** (`?`) — nabij hlavou zespodu → vyskočí **dočasný power-up**. Jsou vzácné: 1 na level, od levelu 20 dva, od levelu 40 tři.
  - ⭐ **Hvězda** (12 s) — nezranitelnost + zabíjíš nepřátele dotykem
  - ⚡ **Rychlost** (30 s) — běháš rychleji
  - 🦘 **Super skok** (30 s) — vyskočíš výš
  - 🧲 **Magnet** (30 s) — přitahuje mince
  - 🔥 **Oheň** (16 s) — automaticky střílíš ohnivé koule, které zabíjejí nepřátele (i bossy)
  - 🕊️ **Křídla** (18 s) — držením skoku plachtíš vzduchem
  - ⏰ **Zpomalení** (12 s) — nepřátelé a projektily zpomalí, ty ne
  - Aktivní power-up má vlevo nahoře ikonu s odpočtem.
- 🪙 Sbírej mince. Po dokončení levelu se přičtou do **peněženky** (utrácíš je v obchodě). 1 mince = 1 bod.
- 🧗 **Wall jump** — u zdi ve vzduchu zmáčkni skok a odrazíš se od ní (jde i vyšplhat).
- ☔ **Počasí** — každý svět má atmosféru: sníh (led), déšť (hrad), jiskry (sopka), spory (houby).
- 🟢 **Trampolíny** — dopadni na ně a vymrští tě mnohem výš než skok.
- 🔺 **Bodáky** — musíš je přeskočit, dotek ubere život.
- ⏳ **Mizející plošiny** — jakmile na ně stoupneš, za chvíli zmizí (a pak se vrátí) — pospěš si.
- 🕳️ Nespadni do díry. ❤️ 3 životy (dá se rozšířit upgradem).
- 🔗 **Combo** — zabíjej nepřátele rychle za sebou, řetěz dává čím dál víc coinů (u zabití naskočí „COMBO ×N"). Zásah combo přeruší.
- ✨ Vyskakující čísla (+N), screen shake a hit-stop záškub pro šťavnatější pocit.
- 👑 **Bossové** — každý 10. level (10, 20, 30, 40, 50) je boss aréna: velký nepřítel s **health barem** a **3 fázemi** (čím míň HP, tím zuřivější — víc projektilů a skoků). Zašlápni ho shora, poraz ho a projdi k vlajce. HP roste s levely (3→7), za poražení je tučný coin bonus.
- 🏁 Na konci levelu je **vlajka** → oslava 🎉 a dialog **Pokračovat / Menu**.
- Bez časového limitu.

## Herní módy
Tlačítko **🎯 Herní módy** v menu — hraj hru jinak (nejlepší výsledky se ukládají):
- ⏱️ **Time Attack** — závod o čas, vedle tebe běží 👻 duch tvého rekordu.
- 💰 **Coin Rush (60 s)** — nasbírej co nejvíc mincí za minutu.
- 💀 **Hardcore (1 život)** — jediný zásah a končíš.
- 👑 **Boss Rush** — jen boss arény za sebou (level 10 → 20 → 30…). Poraz bosse a jdeš rovnou na dalšího.
- 🧘 **Zen (bez nepřátel)** — žádné příšery ani bodáky, jen skákání a sbírání. Na vydechnutí.
- 🗓️ **Výzva týdne** — každý týden jiný level s lokálním rekordem (viz níže).

## 🛠️ Editor levelů (creator)
Tlačítko **🛠️ Editor levelů** v menu. Postav si vlastní level v mřížce 40×15:
- **Paleta dlaždic** — guma, země, cihla, ❓ lucky blok, 💰 mince, roura, 🔺 bodáky, 🟢 trampolína, 🚧 brána, 👾 nepřítel, 🦇 létající, 🧍 start, 🚩 cíl. Vyber nástroj a **klikni/táhni** do mřížky.
- **▶ Vyzkoušet** — zahraj svůj level rovnou (bez odměny mincí, ať se nedá farmit).
- **💾 Uložit** — level se uloží do „Moje levely" (hrát / upravit / smazat).
- **📤 Sdílet kód** — vygeneruje textový kód levelu do schránky. Pošli ho kámošovi.
- **📥 Načíst kód** — vlož kód od kámoše a zahraj/uprav jeho level. (offline sdílení levelů mezi hráči)

## 🗓️ Výzva týdne
Herní mód **🗓️ Výzva týdne** — každý týden jiný level (deterministicky podle čísla týdne, pro všechny stejný) s vlastním **lokálním rekordem** (nejvíc mincí). Rekord se ukazuje v přehledu Herních módů.

## ♻️ Rebirth (prestige)
V obchodě nahoře je sekce **Rebirth**. Za nasbírané mince koupíš rebirth (cena roste: 1000, pak +2500 za každý další). Každý rebirth:
- **+1 max úroveň všech upgradů** (můžeš je vylepšit výš, než šlo)
- **+10 % mincí navíc** ze všeho, co sesbíráš (kumulativně)

Klasický prestige loop — resetuješ mince do trvalé síly a rosteš rychleji.

## Závod & sdílení (lokální)
- 👻 **Ghost race** — v Time Attacku vedle tebe závodí **průhledný duch tvého nejlepšího běhu**. Poraz sám sebe!
- 📤 **Sdílení výsledku** — po levelu tlačítko „Sdílet" vygeneruje obrázek s tvým výsledkem (level/čas/coiny) k poslání kámošům.
- 🏅 **Rekordy** — Coin Rush rekord, nejrychlejší časy, nejdál v endless (v obrazovce Herní módy).

- 🔗 **Sdílení hry** — v Nastavení tlačítko „Poslat odkaz kámošovi" (přes systémové sdílení / zkopíruje odkaz).
- 🛠️ **Sdílení vlastních levelů** — přes kód v editoru (viz Editor levelů) si hráči můžou posílat levely mezi sebou i offline.

> Pozn.: Globální online (žebříček **všech** hráčů, porovnání s přáteli v reálném čase, celosvětový turnaj) potřebuje server — hra je jeden lokální soubor. Proto jsou tu **lokální ekvivalenty**: lokální rekordy (Coin Rush, časy, endless, výzva týdne), ghost race, sdílení výsledku obrázkem a sdílení levelů/odkazu kódem. Globální verze se doplní nasazením na web + backendem (Firebase/Supabase).

## Progrese & odměny
- ⭐ **Hvězdy za levely** (1–3) podle toho, kolik mincí v levelu sesbíráš. Zobrazí se u dokončení i ve výběru levelů.
- 🏆 **Trofeje** (tlačítko v menu) — 8 achievementů (zabij X nepřátel, poraz bosse, dosáhni comba…), za každý odemčený je coin odměna. Odemčení oznámí vyskakovací notifikace.
- 📊 **Statistiky** — dohrané levely, zabití nepřátelé, poražení bossové, nasbírané mince, nejlepší combo, úmrtí.

## Pauza (během hry)
Vpravo nahoře je **⏸ tlačítko** (nebo klávesa `P` / `Esc`). Otevře pauzu s možnostmi:
- **▶ Pokračovat**
- **↻ Restart levelu** — když se něco zasekne nebo chceš level znovu
- **💾 Uložit a do menu** — uloží postup a vrátí do menu; „Hrát" tě pak vrátí přesně k tomuto levelu

Postup (odemčené levely, mince, skiny, upgrady, naposledy hraný level) se navíc ukládá **automaticky** do prohlížeče, takže o nic nepřijdeš ani při zavření.

## Menu a progrese
- **Hlavní menu:** Hrát (pokračuje od naposledy hraného levelu) · Levely · Obchod · 🔄 Resetovat postup (s potvrzením — smaže mince, odemčené levely, skiny i upgrady)
- **Levely:** mřížka 50 levelů, odemykají se postupně (dokončením předchozího). Dokončené mají ✓.
- **Obchod (za mince):**
  - **Skiny:** Kuba (základní), Ninja, Minťák, Vodník, Robot, Zlaťák, Král
  - **Upgrady (permanentní):** Extra srdce (víc životů) · Vyšší skok · Rychlost · Magnet · 🪂 Trojskok (třetí skok ve vzduchu) · 💰 Zlaté prsty (každá mince dá o 1 coin víc) · ⏳ Delší power-upy (trvají o 40/80 % déle) · 🛡️ Startovní štít (každý level začneš se štítem na 1 zásah)
- **Ukládání:** peněženka, odemčené levely, koupené skiny a upgrady se ukládají do prohlížeče (localStorage). Postup zůstane i po zavření.

## Levely a světy (biomy)
🔄 **Nekonečná hra:** po dokončení 50. levelu hra pokračuje **náhodnými levely donekonečna** — biomy se cyklí dokola, bossové jdou dál každý 10. level a obtížnost roste. Jak nejdál dojdeš?

50 procedurálně generovaných levelů s **rostoucí obtížností** (delší, víc příšer, víc bran a děr, rychlejší nepřátelé). Generátor je deterministický (level N je vždy stejný). Všech 50 je ověřeno: každá mince je dosažitelná, žádná brána nevisí nad dírou, žádná díra není širší, než zvládne dvojskok.

Levely procházejí **8 různých světů**, každý s vlastními barvami, pozadím, překážkami a příšerou:

| Svět | Vzhled | Příšera |
|------|--------|---------|
| 🌱 Louka | zelená, den, slunce | Goomba (hřib) |
| 🏜️ Poušť | oranžová, kaktusy | Brouk |
| ❄️ Ledová pláň | modrobílá, sníh | Tučňák |
| 🦇 Jeskyně | noc, krystaly | Netopýr (**létá**) |
| 🌋 Sopka | rudá, láva | Ohnivec (**létá**) |
| 🍄 Houbový les | fialová, houby | Sliz |
| ☁️ Nebe | světlá, mraky | Ptáček (**létá**) |
| 🏰 Temný hrad | tmavá, náhrobky | Duch |

Létající příšery poletují ve vzduchu a zašlápneš je dvojskokem stejně jako ostatní.

## Struktura
- `index.html` — celá hra (canvas + JS + WebAudio zvuky, vše inline)
- `README.md` — tento soubor

## Jak spustit
Dvojklik na `index.html`, nebo:
```bash
open index.html
```
Případně nasadit kamkoliv jako statický web (Vercel, Netlify, GitHub Pages) — je to jeden soubor.

## Stav
✅ Hratelné a kompletní. 50 levelů + nekonečná hra, 🛠️ **editor levelů** (creator) + sdílení kódem, 6 herních módů (Time Attack, Coin Rush, Hardcore, Boss Rush, Zen, 🗓️ Výzva týdne), ♻️ rebirth/prestige, 🎵 hudba, ⌨️ ovládání menu klávesnicí, 🌍 dvojjazyčnost (CS/EN) + ⚙️ nastavení, 🎮 přihlášení přezdívkou, menu, výběr levelů, obchod se skiny a upgrady, ukládání postupu, dvojskok + auto-skok, bossové, oslava po levelu, vylepšená grafika (parallax, slunce, stíny, konfety). Funguje na desktopu i mobilu.

> Připravené příště: nasazení jako **veřejná URL** (Vercel) + volitelný backend pro skutečný globální žebříček.

Pozn.: v souboru je neškodný debug hook `window.__kuba` a error logger `window.__err` (sloužily k testování hry v konzoli, nezávisle na fps) — na hraní nemají vliv.

## Nápady na rozšíření
- Vlastní avatar Kuby (jeho foto), víc skinů a upgradů
- Nové typy nepřátel, pohyblivé plošiny, power-upy v levelu
- Bossové na konci sekcí (např. každý 10. level)
- Online žebříček / sdílení výsledků
