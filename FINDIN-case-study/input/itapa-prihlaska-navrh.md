# Findin.sk — návrh textu pre prihlášku do súťaže ITAPA

> Pracovný návrh. Čísla a fakty sú overené (findin-brief.md), formulácie
> zámerne "chrumkavé/úderné" podľa zadania. Priestor na úpravu podľa
> presného formulára ITAPA (sekcie/limity znakov) mi daj vedieť.

---

## Názov projektu
**Findin.sk — digitálna vizitka slovenského biznisu pre svet**

## Jednou vetou
Portál, ktorý z roztrúsených e-mailov a tabuliek urobil jedno miesto, kde
dnes nájdete takmer 650 slovenských firiem pripravených na medzinárodný
biznis.

---

## Výzva

Slovensko malo stovky firiem pripravených expandovať za hranice, ale
nemalo spôsob, ako ich ukázať svetu naraz, na jednom mieste. Prezentácia
slovenského biznisu smerom von bola roztrieštená, informácie sa posielali
e-mailom, podujatia sa spravovali ručne a zahraniční partneri nemali kde
jednoducho overiť, kto na Slovensku skutočne pôsobí a v čom je dobrý.

SARIO potrebovalo nie ďalší formulár, ale **centrálny digitálny nástroj**,
ktorý dokáže niesť tri úplne odlišné úlohy naraz: prezentáciu firiem,
správu medzinárodných podujatí a informačný servis pre verejnosť, a ešte
k tomu zostať naviazaný na interné systémy agentúry v reálnom čase.

## Riešenie

Vznikol **Findin.sk** — plne responzívny digitálny portál postavený od
základov na modernom open-source stacku (Docker Swarm, NuxtJs, VueJS, PHP),
hostovaný vo vládnom cloude, aby zvládol nároky verejnej správy na
bezpečnosť a dostupnosť.

Pred prvou líniou kódu sme urobili niečo, čo sa pri štátnych projektoch
bežne preskakuje: **rozsiahly používateľský výskum**. Výsledkom je
rozhranie, ktoré firmy aj zahraniční partneri ovládajú bez návodu.

Portál je **plne integrovaný s internými systémami SARIO cez REST API**,
s automatickou obojsmernou synchronizáciou veľkých objemov dát. Firmy si
dnes upravujú vlastný profil online, namiesto posielania zmien e-mailom.
SARIO organizuje a spravuje medzinárodné podujatia na jednom mieste,
namiesto roztrúsenej administratívy.

## Výsledky, ktoré hovoria samy za seba

- **Takmer 650 kompletne vyplnených profilov slovenských firiem** je dnes
  verejne dostupných na jednom mieste, ďalších vyše **850 firiem** má
  aktivovaný profil a čaká na zverejnenie.
- Portál ročne zaznamenáva **77-tisíc zobrazení a 187-tisíc interakcií** —
  dôkaz, že nejde o ďalší "zabudnutý vládny web", ale o nástroj, ktorý
  odborná aj širšia verejnosť reálne používa.
- Predtým neexistoval žiadny porovnateľný systém. Findin.sk tak nie je
  vylepšením niečoho starého — je to **prvý centralizovaný nástroj svojho
  druhu na Slovensku**, ktorý spája prezentáciu firiem, podujatia aj
  informačný servis do jednej platformy.
- Projekt vznikol v rámci národného projektu Podpora internacionalizácie
  MSP a priamo podporuje cieľ, ktorý je pre slovenskú ekonomiku kľúčový:
  **dostať slovenské firmy za hranice**.

## Prečo by mal Findin.sk získať ocenenie

Pretože je to presne ten typ digitalizácie, o ktorej sa veľa hovorí a
málokedy sa reálne podarí: **projekt, ktorý nahradil papiere a e-maily
jedným moderným nástrojom a ľudia ho naozaj používajú.** Nie je to portál,
ktorý vznikol, aby splnil checklist. Je to nástroj, vďaka ktorému má dnes
takmer 650 slovenských firiem jednoduchšiu cestu k zahraničným partnerom,
než mali kedykoľvek predtým.

---

## Poznámky k faktom (pre kontrolu, nedávať do prihlášky)
- 650+ profilov / 850+ so záujmom, 77-tis. zobrazení, 187-tis. interakcií
  — priamo od Petry Sasinkovej (SARIO), e-mail 29.9.2026.
- "Prvý svojho druhu" — oprieť sa o fakt klienta "žiadny obdobný systém
  predtým k dispozícii nebol" (z toho istého e-mailu). Ak si nie sme 100%
  istí, že neexistuje iný porovnateľný portál na Slovensku, treba toto
  tvrdenie zjemniť alebo vyňať.
- Technológie, REST API integrácia, vládny cloud, user research — priamo
  z brief/scrtechnologies.sk.
