Mollvero — podklad pre case study

# Mollvero — z 30-ročnej výrobnej tradície vznikla digitálna značka nábytku na mieru

Za značkou Mollvero stojí spoločnosť Lukamasiv, ktorá začínala v roku 1997 v Kriváni s jediným zamestnancom. Dnes je to jeden z popredných slovenských výrobcov nábytku a nábytkových komponentov: 82 zamestnancov, 7 200 m² výrobných plôch, viac ako 435 000 vyrobených komponentov mesačne a export do 5 krajín (Slovensko, Česko, Poľsko, Litva, Švédsko) — vrátane dlhoročných dodávok pre známu švédsku nábytkársku spoločnosť. Viac ako 70 % výroby je plne automatizovanej, od CNC robotických pracovísk až po robotické lakovanie.

V roku 2023 firma urobila strategický obrat: rozhodla sa využiť know-how zo sériovej výroby a zamerať sa priamo na koncového zákazníka. Otázka znela: ako preniesť desaťročia výrobného know-how priamo k ľuďom, ktorí chcú nábytok na mieru? Odpoveďou bola nová značka Mollvero — a s ňou zadanie pre SCR technologies: postaviť digitálny predajný kanál, kde si zákazník sám navrhne nábytok presne na mieru a objedná ho online.

Digitalizácia prebehla v dvoch krokoch: najprv partnerská B2B zóna napojená na podnikové systémy a po nej verejný e-shop mollvero.sk s 3D konfigurátorom. Zákazník sa stáva „dizajnérom svojho domova" — a výroba dostáva objednávku pripravenú tak, že ju vie dodať do 14 dní.

# 1. Zadanie a výzva

Hlavný problém: Nábytok na mieru sa nedá predávať klasickým e-shopom. Každý kus je iný — rozmery na milimeter presne, desiatky dekorov, rôzne korpusy, dvierka, kovania. Bežný e-shop s pevnými produktmi a cenami tu nefunguje a manuálne naceňovanie každého dopytu obchodníkom sa nedá škálovať.

Prečo to bolo dôležité riešiť: Lukamasiv mal výrobnú kapacitu aj procesy (70 % automatizácia, dodanie za 14 dní), ale chýbal mu priamy digitálny kanál ku koncovému zákazníkovi. Predaj cez dopyty e-mailom a telefonicky znamenal pomalé naceňovanie, zaťaženie obchodníkov rutinou a stratené príležitosti mimo pracovného času.

Ako to fungovalo predtým: Celý predaj koncovým zákazníkom prebiehal výlučne offline — išlo o greenfield projekt, prvý online predajný kanál v histórii firmy. Zákazník poslal dopyt, obchodník ručne pripravoval návrh a cenovú ponuku, komunikácia prebiehala tam a späť. Každá zmena rozmeru či dekoru znamenala nové kolo — a ručný prenos konfigurácií do výrobných systémov zvyšoval riziko chýb a následných reklamácií.

Očakávania klienta: Plnohodnotný e-shop, kde si zákazník produkt sám nakonfiguruje (rozmery, dekory, varianty) a hneď vidí cenu; B2B zóna pre partnerov; správa obsahu vo vlastných rukách; a napojenie na výrobný softvér, aby web a výroba pracovali s rovnakými dátami.

# 2. Návrh riešenia a analýza

Nezačali sme dizajnom ani kódom. Spolupráca sa začala už v roku 2024 detailnou analýzou a návrhom partnerskej B2B zóny — najprv sme pochopili, ako v Lukamasive vzniká a predáva sa nábytok: od konfigurácie cez výrobné podklady, cenotvorbu a fakturáciu až po montáž u zákazníka. Výstupom prípravnej fázy bola kompletná funkčná špecifikácia vo forme interaktívnej wiki, technologická architektúra, grafické návrhy a harmonogram s míľnikmi — až potom sa začalo programovať.

Kľúčovým zistením analýzy bolo, že firma stojí na dvoch systémoch: Helios ERP (obchodné dáta — zákazníci, objednávky, ceny, faktúry) a IMOS (CAD/CAM softvér pre nábytkársku výrobu, v ktorom sú definované produkty, varianty a konštrukčné parametre).

Z toho vyplynul základný architektonický princíp: web nesmie byť ďalšou izolovanou databázou. Riešenie je konektormi napojené na oba systémy — to, čo si zákazník nakonfiguruje a objedná, je priamo previazané s tým, čo výroba vie vyrobiť a čo obchod vie vyfakturovať.

Druhým pilierom bol 3D konfigurátor — najdôležitejší a najnáročnejší prvok celého riešenia. Musí zvládnuť rozmery na mieru, výber dekorov a variantov, priebežný prepočet ceny, vizualizáciu výsledku a na konci odovzdať objednávku so všetkými parametrami pre výrobu.

Tretím pilierom bola dvojkanálovosť: rovnaký základ obsluhuje B2B partnerov (vlastná zóna, cenové podmienky, účty) aj B2C zákazníkov (verejný e-shop).

# 3. Popis riešenia v praxi

Pre zákazníka (B2C): Na mollvero.sk si vyberie produkt zo 6 kategórií (detská izba, spálňa, kúpeľňa, obývacia izba, predsieň, pracovňa) a v konfigurátore si ho prispôsobí: rozmery na mieru, 21 farebných kombinácií a pri najbohatších produktoch až 219 variácií — dokopy tisíce možností, ako si jeden kus nábytku upraviť presne podľa seba. Cenu vidí okamžite a objedná kedykoľvek, 24/7. Súčasťou procesu je 3D návrh zdarma a konzultácia s dizajnérom, výroba a dodanie do 14 dní vrátane inštalácie. Nábytok je 100 % rozoberateľný — navrhnutý tak, aby sa dal sťahovať a skladať opakovane.

Pre B2B partnerov: Samostatná B2B zóna s registráciou a prihlásením, zvýhodnenými cenami a vlastným account manažérom. Partner má v zóne k dispozícii dashboard, objednávky, cenové ponuky, faktúry aj reklamácie — synchronizované s podnikovým systémom Helios ERP, takže vidí vždy aktuálne dáta bez telefonátov a e-mailov. Architekti a dizajnéri majú navyše 3D databázu všetkých produktov (formáty OBJ, FBX, SKP) pripravenú na priame použitie vo vizualizáciách.

Pre tím Mollvero: Administrácia (CMS), v ktorej si sami spravujú produkty, fotografie, dekory, texty, benefity produktov, bannery aj obsahové stránky — bez zásahu programátorov. Objednávky prichádzajú so všetkými parametrami konfigurácie pripravenými pre výrobu.

Čo z toho má iná firma (prenositeľnosť): Rovnaký model — konfigurátor + synchronizácia s výrobným systémom + B2C/B2B kanály — je použiteľný pre akéhokoľvek výrobcu produktov na mieru, ktorý chce predávať online bez armády obchodníkov.

# 4. Implementácia a technológie

Fázy projektu: analýza a návrh → vývoj (iteratívne, s priebežnými ukážkami) → UAT testovanie s klientom → akceptácia a spustenie — najprv B2B zóna pre partnerov, následne verejný e-shop (2026) → prevádzka a rozvoj v SLA režime (kontinuálne change requesty).

Technológie a prečo:

Nuxt (Vue.js) — frontend so server-side renderingom: rýchly, responzívny web s plnou podporou SEO (meta tagy, Open Graph, sitemap generované na serveri). Web funguje ako moderná single-page aplikácia — prekliky sú okamžité.

October CMS (Laravel) — administrácia a backend: overená kombinácia, klient si spravuje celý obsah sám v prehľadnom rozhraní.

Keycloak — bezpečnosť a správa používateľov: enterprise štandard pre autentifikáciu, používaný aj vo veľkých korporátnych prostrediach. Rieši účty zákazníkov aj B2B partnerov vrátane obnovy hesiel a rolí.

Konektor Helios ERP — obchodné dáta (zákazníci, objednávky, cenové ponuky, faktúry) synchronizované medzi B2B zónou a podnikovým systémom.

Konektor IMOS — konfigurovateľné produkty a ich parametre tečú z výrobného systému do webu; jeden zdroj pravdy pre výrobu aj predaj.

Thumbor + objektové úložisko — automatická optimalizácia obrázkov (resize, WebP/JPEG, responzívne varianty) pre rýchle načítanie na každom zariadení.

Google Tag Manager s consent mode — merania v súlade s GDPR: analytické nástroje sa načítajú až po súhlase návštevníka.

XML feed pre Google Merchant — produkty pripravené pre Google Nákupy a ďalšie platformy (architektúra počíta s rozšírením o Heureku a affiliate siete).

Prostredia: tri oddelené prostredia — vývojové, testovacie/UAT (test.mollvero.sk) a produkčné. Každá zmena prechádza cez UAT test klienta pred nasadením na produkciu.

Kvalita a prevádzka: pred spustením prebehlo kompletné testovanie — integračné, funkčné, regresné, výkonové aj bezpečnostné testy a UAT so zástupcami klienta. Go-live mal plánované nasadzovacie okno s rollback plánom a intenzívnou podporou po spustení. Súčasťou riešenia je CI/CD, monitoring prostredia, zálohovanie a obnova. Dodávka zahŕňala aj audit prístupnosti WCAG.

Nástroje a proces: Git, JIRA (transparentný proces: klient vidí a schvaľuje tickety vo vlastnom projekte), pravidelné releasy s release notes, dokumentácia v interaktívnej wiki.

# 5. Výsledky a dopad

Zákazník si dnes navrhne a objedná nábytok na mieru bez jediného telefonátu — z tisícov možností, s cenou vypočítanou okamžite. Obchodníci sa venujú konzultáciám a náročnejším projektom namiesto rutinného naceňovania.

Objednávky môžu vznikať 24/7 — konfigurátor pracuje aj vtedy, keď má obchod aj výroba voľno.

Cenová ponuka, na ktorú sa predtým čakalo, sa počíta v reálnom čase — pri každej zmene rozmeru či dekoru.

Objednávka prichádza do výroby so všetkými parametrami konfigurácie — bez prepisovania a bez chýb z ručného prenosu.

Tím Mollvero spravuje celý obsah webu vlastnými silami — od produktov a fotiek po bannery kampaní, bez čakania na dodávateľa.

Manažment má objednávky, konfigurácie aj správanie zákazníkov merateľné na jednom mieste.

# 6. Dlhodobý prínos a rozvoj

Web bol od začiatku stavaný ako platforma, nie jednorazová dodávka. Od spustenia kontinuálne rastie v SLA režime — už prvé mesiace prevádzky priniesli sériu vylepšení: editovateľné benefity produktov, priraďovanie dekorov a farieb, indikátory variácií, nový layout detailu produktu, reklamné bannery v katalógu, XML feed pre Google Merchant, Open Graph náhľady pre zdieľanie na sociálnych sieťach či kompletné konverzné merania pre marketingové kampane.

Kam ďalej: rozvoj marketingových meraní a kampaní (Meta Pixel, GA4) a rozširovanie katalógu. SCR technologies je pri tom ako dlhodobý technologický partner.

# 7. Partnerstvo s klientom

Spolupráca funguje na dennej báze cez zdieľaný JIRA projekt — klient zadáva požiadavky, vidí ich stav a testuje nasadenia na UAT prostredí pred každým releasom. Vízia sa formovala spoločne: klient priniesol hlboké znalosti výroby a trhu, SCR technologies technológie a skúsenosti s digitálnymi predajnými kanálmi.

Kľúčovým momentom bolo samotné spustenie — najprv B2B zóny pre partnerov a následne verejného e-shopu. Riešenie, ktoré dovtedy žilo v návrhoch a na testovacom prostredí, začalo prijímať reálne objednávky.

Nie sme dodávateľ, ktorý odovzdá web a zmizne. Mollvero má partnera, ktorý pozná ich výrobu, ich zákazníkov aj ich plány — a web, ktorý rastie spolu s firmou.

# Čísla pre case study (banka čísel pre dizajn)

Návrh 4 hero čísel (štýl Galia):

Číslo

Popis

Zdroj

30+

rokov výrobných skúseností (Lukamasiv od 1997)

mollvero.sk

14 dní

od objednávky po dodanie a inštaláciu

mollvero.sk

2 372+

spokojných zákazníkov

mollvero.sk (counter)

24/7

online konfigurátor a objednávanie

riešenie

Alternatívna sada do hero, ak chce marketing zdôrazniť výrobnú silu: 435 000+ komponentov mesačne · 7 200 m² výroby · 82 zamestnancov · 5 krajín exportu. Výber a kombinácia sú na marketingu — obe sady sú overené.

Ďalšie overené čísla do sekcií:

435 000+ vyrobených komponentov mesačne (lukamasiv.sk — presne 435 287)

7 200 m² výrobnej plochy (lukamasiv.sk)

82 zamestnancov (lukamasiv.sk)

5 krajín exportu — SK, CZ, PL, LT, SE (lukamasiv.sk)

99,86 % spokojnosť zákazníkov (mollvero.sk/o-nas)

70 %+ výroby plne automatizovanej (mollvero.sk/o-nas)

98 % dreveného odpadu spracovaného do peletiek, 15 % spotreby z fotovoltiky (udržateľnosť — mollvero.sk/o-nas)

219 variácií najbohatšieho produktu v konfigurátore (šatníková skriňa miestta)

21 farebných kombinácií pri každom produkte

tisíce možností, ako si prispôsobiť jeden kus nábytku (rozmery × dekory × variácie)

6 kategórií nábytku v katalógu

2 predajné kanály na jednej platforme (B2C e-shop + B2B zóna)

5 krokov od konfigurácie po inštaláciu

3 formáty 3D modelov pre architektov (OBJ, FBX, SKP)

100 % rozoberateľný nábytok

3D návrh zdarma ku každej objednávke

2 generácie rodinnej firmy

3 oddelené prostredia (dev / UAT / produkcia)

2 podnikové integrácie: Helios ERP (obchod) + IMOS (výroba)

1 zdroj pravdy: dáta synchronizované priamo z podnikových systémov

# Podklady pre finálnu stránku (štýl Galia)

Kategória/tagy do hero: Výroba a e-commerce · E-shop s konfigurátorom · B2C + B2B

Návrh hero headline: „Od výroby pre svetové značky k vlastnému e-shopu na mieru" (alt: „Nábytok na mieru, ktorý si zákazník navrhne sám")

Fact box: Klient: Mollvero (member of Lukamasiv®), Kriváň · Odvetvie: výroba nábytku / e-commerce · Riešenie: e-shop s 3D konfigurátorom + partnerská B2B zóna, integrované so systémami Helios ERP a IMOS · Spustenie: 2026 · Web: mollvero.sk

Quote majiteľa (už existuje na webe, možno použiť):

„Náš zákazník nechodí do obchodu hľadať kompromisy. My ideme na milimeter presne."

— Ľubomír Očenáš, majiteľ

Návrh CTA na záver: „Vyrábate produkty na mieru a chcete ich predávať online? Ozvite sa nám."
