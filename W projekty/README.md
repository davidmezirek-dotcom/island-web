# GeoMag – Školní projekt (Magazín o Islandu)

Autor: David Mezírek  


Webový magazín o sopkách, gejzírech a přírodě Islandu. Web je postavený na sémantickém HTML5, responzivních obrázcích v moderním formátu WebP a jednoduchém CSS stylu s pergamenovým pozadím a tmavě červenými akcenty.

---

## Odkazy na projekt

- **GitHub repozitář:** [ZDE VLOŽTE ODKAZ NA VÁŠ GITHUB]
- **Web na školním serveru:** [ZDE VLOŽTE ODKAZ NA ŠKOLNÍ SERVER]

---

## Wireframe (Návrh rozvržení)

- Návrh rozvržení pro stránku článku (`detail.html`) je přiložen v kořenu projektu jako soubor `wireframe.png` (případně naskenovaný nákres na papíře).

---

## Přehled splněných požadavků

Všechny body ze zadání jsou zapracované takto:

- **Struktura webu (3 stránky):**
  - `index.html` – úvodní stránka s představením magazínu a kartami článků (první karta má funkční proklik na detail, další dvě slouží jako ukázky).
  - `detail.html` – samotný článek o expedici na Island.
  - `kontakty.html` – kontaktní údaje redakce s mapou a otevírací dobou.
  - Všechny stránky mají v hlavičce i patičce funkční navigaci s označením aktivní stránky pomocí `aria-current="page"`.

- **Sémantické značky (Landmarky):**
  - Použity `<header>`, `<nav>`, `<main>`, `<footer>`, `<article>`, `<section>` a `<aside>`.
  - Stránky nejsou poskládané z prázdných `<div>`, ale mají logické rozvržení.

- **Mikrosémantika a typografie:**
  - `<hgroup>` pro spojení hlavního nadpisu a podtitulku na všech stránkách.
  - `<time>` se strojovým atributem `datetime` pro data publikace a otevírací dobu.
  - `<aside>` na stránce článku slouží jako glosář odborných sopečných pojmů (`<dl>`, `<dt>`, `<dfn>`, `<mark>`).
  - `<address>` na stránce kontaktů pro adresu redakce a kontaktní spojení.

- **Média a grafika:**
  - **SVG logo:** Vektorové logo magazínu `logo.svg` v hlavičce každé stránky.
  - **Moderní formát WebP:** Všechny fotky jsou převedené do formátu `.webp`, žádné staré JPG ani PNG.
  - **Responzivní obrázky (`srcset`):** Na stránce článku (`detail.html`) je celkem 5 fotek s nastaveným `srcset`, `sizes` a `loading="lazy"`.
  - **Vložený obsah (`<iframe>`):** Na detailu je vložené YouTube video z dronu nad sopkou, v kontaktech je vložená interaktivní mapa přes OpenStreetMap.

- **Patička:**
  - Na všech stránkách obsahuje jméno (David Mezírek), vymyšlené IČO (12345678) a textovou mapu webu.

---

## Využití AI při tvorbě projektu

Při práci na projektu jsem AI použil jako konzultanta v souladu s pravidly:
- Konzultoval jsem správnou sémantickou strukturu HTML5 (jak správně zanořit `<aside>` do článku a jak funguje `<hgroup>`).
- Pomohla mi vyřešit správný zápis syntaxe u responzivních obrázků (`srcset` a `sizes`).
- Řešil jsem s ní chyby v relativních cestách k souborům a formátování vloženého `<iframe>`.
- Samotný kód, strukturu souborů i finální úpravy textů jsem si skládal a testoval v editoru sám.