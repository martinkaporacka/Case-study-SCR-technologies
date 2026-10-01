# Findin.sk — podklad pre case study (SARIO)

> Zdroj 1: brief zo scrtechnologies.sk/en/case-studies/ (doslovne, EN).
> Zdroj 2: e-mailova komunikacia Ladislav Simko (SCR) <-> Petra Sasinkova (SARIO),
> september 2026 — realne cisla a citaty priamo od klienta.
> Pravidlo: cisla pouzivaj len z tychto zdrojov, nevymyslaj.

## Brief zo scrtechnologies.sk (anglicky, case study page)

**Customer:** The Slovak Investment and Trade Development Agency (SARIO)
**Realization:** 2023 - 2024
**Duration:** 24 months
**Technologies:** Docker Swarm, Nginx, NuxtJs, PHP, Portainer, RabbitMQ, Redis,
S3 Storage, Vladny Cloud (government cloud), VueJS
**Live at:** https://findin.sk/en

### 01. Assignment
Create a digital platform bringing together three key areas:
- presentation of Slovak companies
- event management
- information service for the public

Needed to be easy to understand, simple to use, ready for expansion. Had to
support daily operations without requiring complex interventions, while
allowing future development and integration with other systems.

### 02. Solution
Started with extensive user research -> functional, intuitive, visually
appealing design. In parallel, detailed functional analysis as basis for a
reliable, scalable solution.
Built on modern open-source stack: Docker Swarm, Nginx, NuxtJs, PHP,
Portainer, RabbitMQ, Redis, S3 Storage, VueJS.
Fully integrated via REST API to SARIO's internal systems — seamless
connectivity, automatic synchronization of large amounts of data.
Hosted in the government cloud — high availability and security standards.
Team: frontend + backend developers, tech lead, tester, project manager.

### 03. Result
Fully responsive digital platform, focus on UX. Sections:
- **Companies** — catalogue of Slovak companies, filterable by location,
  number of employees, certificates. Profile details: key info, results,
  business focus. Companies update own details via online form. Tool for
  presenting Slovak industry capacities to foreign partners.
- **Events** — interactive overview of upcoming SARIO events, filterable,
  online registration form. Event detail has contact/organizational info.
- **Archive and information pages** — records of past events + overview of
  SARIO's activities/services.

Findin.sk = strategic tool for supporting exports, building business
partnerships, showcasing Slovak companies globally.
Created within SARIO National Project "Support for the internationalisation
of small and medium-sized enterprises", activity "Development of supply
chains" (RDR).
Design/UX credit: SCR design (sister company, scrdesign.com).

---

## Realne cisla a citaty — z emailu Ladislav Simko / Petra Sasinkova (29.9.2026)

> POZOR: toto su realne, priamo klientom poskytnute udaje. Niektore maju
> explicitny disclaimer od klienta (napr. "s tymto udajom tazko pracovat",
> "n/a") — tie NEPREZENTOVAT ako jednoznacny uspech, format honestne.

**Pocet firiem na portaly:**
- takmer 650 (precizne) vyplnenych profilov
- profil ma aktivovanych vyse 850 spolocnosti, ktore prejavili zaujem o jeho
  zverejnenie (len sa este nedostali k realizacii / nedokoncili)
- "Na platforme findin.sk sa dnes prezentuje takmer 650 slovenskych
  subjektov, pricom dalsi zaujemcovia neustale pribudaju."

**Navstevnost (za uplynuly rok, z analytiky):**
- 77-tisic zobrazeni (vzhliadnuti)
- 187-tisic interakcii
- Klientov komentar: "Tieto udaje potvrdzuju, ze system je aktivne
  vyuzivanym nastrojom s konkretnym dosahom na prezentaciu a podporu
  slovenskych spolocnosti."

**Pocet online rezervacii / ziadosti o zmeny profilu — NEJEDNOZNACNE, pouzit opatrne:**
- V CRM 746 "Aktivne aktualizacie profilov spolocnosti", ALE: "mnohe firmy
  su tam duplicitne. Vacsinu uprav sme robili firmam my manualne v CRM a
  CMS." -> teda tento pocet NIE JE cisty dokaz samoobsluzneho vyuzivania
  portalu, vela bolo rucne spracovane timom SARIO. Nepouzivat ako "650
  automatickych uprav" ci podobne zavadzajuce tvrdenie.

**Uspora casu / financna uspora — explicitne N/A:**
- "Ziadny obdobny system predtym k dispozicii nebol, preto nie je s cim
  porovnat." (ziadne pred/po porovnanie casu)
- Financne uspory: "n/a"

**Digitalizovane procesy — pouzit opatrne, s realnym kontextom:**
- Klientov komentar: "hlavnou usporou mali byt online formulare na
  registraciu na podujatia a tie sa nikdy (vzhladom na nutnost uprav)
  nepouzili." -> event registracny formular NEPOUZIVAT ako hotovy uspech,
  je to funkcia ktora existuje ale realne sa nevyuziva v planovanej miere.
- V malej miere sa vyuziva: Sourcing enquiry form, Vseobecny kontaktny
  formular, formulare na upravu profilu (tie "vyrazne znizuju cas oproti
  manualnym upravam" — toto MOZNO pouzit, je to pozitivne a konkretne).

**Dalsi marketingovy text od klienta (SARIO o portali, mozne pouzit ako kontext):**
> Prostrednictvom verejnej platformy sluzi sirokej odbornej verejnosti na:
> - bezplatnu a na jednom webovom sidle centralizovanu prezentaciu aktivit
>   slovenskych spolocnosti navonok
> - ziskavanie informacii o slovenskych spolocnostiach na jednom verejne
>   dostupnom webovom sidle
> - podporu internacionalizacie slovenskych podnikov a zviditelnovanie
>   slovenskeho podnikatelskeho prostredia v zahranici
> - identifikaciu vhodnych kooperacnych partnerov zo Slovenska z domu i zo
>   zahranicia
> - moznost zadavania kooperacnych dopytov online

**Citaty / spatna vazba — DOLEZITE: TYTO CITATY SU OD FIRIEM SMEROM K SARIO
(hodnotia SARIO ako agenturu/sluzbu), NIE su to testimonialy o praci SCR
technologies na platforme. Except: dve kratke reakcie nizsie sa tykaju
PRIAMO vzhladu/spracovania portalu, tie SU relevantne pre SCR, ale bez
menoveho pripisania (nevieme kto presne to povedal) — podla pravidla
"ziadny vymysleny citat s menom" ich NEPOUZIVAT ako plnohodnotny
testimonial s podpisom, len mozno parafrazovat v texte ak vobec.

Priamo o portali/dizajne (potencialne pouzitelne, bez mena):
- "vyzera to dobre, mate to velmi pekne spravene celu tu grafiku – strucne
  a prehladne."
- "vyzera to super. Dakujeme velmi pekne, dobra praca."

O SARIO ako agenture (NEPOUZIVAT ako testimonial o SCR):
- "...spoluprace s agenturou SARIO bola pre nas vzdy prinosna..."
- "...velmi pekne Vam dakujem za bleskove spracovanie informacii a
  uspesne zalistovanie mojej spolocnosti na portali findin.sk..."
- "...velmi si vazim vasu ponuku na upravenie... tá neuveritelna snaha
  pomoct."

**Prieskum (realizovany zaciatkom roka 2026, primarne o sourcingu, jedna
otazka o Findin — SLABSIE/NEJEDNOZNACNE DATA, klient sam upozornuje na zle
nacasovanie, POUZIT OPATRNE alebo radsej vynechat z hlavnych cisel):**
- Oslovenych: 171 MSP (ucastnici predchadzajucich sourcingov)
- Reakcii: 88 (51,46 % navratnost)
- Otazka: "Ako vnimate moznost bezplatnej prezentacie Vasej spolocnosti na
  portali Find in Slovakia?"
  - prinosna: 29 (33 %)
  - rad/rada by som ziskal/a viac informacii: 24 (27 %)
  - zatial nie je mozne jednoznacne posudit: 35 (40 %)
