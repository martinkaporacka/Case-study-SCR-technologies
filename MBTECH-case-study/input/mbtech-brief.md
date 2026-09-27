# MBTECH BB — podklad pre case study (Digitálna platforma)

> Zdroj 1: brief od Maty (case study zo scrtechnologies.sk/case-studies/, doslovne).
> Zdroj 2: dohladane cisla z internetu (Finstat, techsavers.sk/o-nas, mbtech.sk) — oznacene nizsie.
> Pravidlo: cisla o firme MBTECH pouzivaj len z tychto zdrojov, nevymyslaj.

## Brief od klienta/marketera (SCR case studies page)

**Nazov spolocnosti:** MBTECH BB s.r.o.
**Rok realizacie:** 2024 - 2025
**Trvanie projektu:** stale trva
**Technologie:** Docker, Keycloak, Nginx, NuxtJs, PHP, Portainer, RabbitMQ, Redis, S3 Storage, Vue

### 01. Zadanie

Digitalna platforma digitalizujuca procesy vo firme s vizualizaciou vystupov a KPI v dashboardoch.

Motivaciou pre pristupenie k digitalizacii procesov vo firme bola hlavne potreba
zefektivnenia prace zamestnancov, zachytenie pohybu a akcii vykonavanych na tovare
v digitalnej podobe a na jednom mieste, jednoduche spristupnenie informacii vsetkym
zamestnancom na jednom mieste a v neposlednom rade ziskat informacie potrebne
k manazerskemu rozhodovaniu.

Klient sa totiz potykal s tym, ze mnozstvo informacii bolo roztriestenych v roznych
systemoch a zdrojoch, pricom viacere vychadzali len z rucne vypisovanych tabuliek,
niektore procesy vo vyrobe neboli digitalizovane vobec alebo len ciastocne, oddelenia
ziskavali informacie navzajom neskoro alebo bolo ich ziskanie velmi obtiazne, co
viedlo k neefektivne vykonavanym cinnostiam.

Ciele projektu:
- hlavnym cielom projektu bolo vytvorit pre klienta Digitalnu platformu ako hlavny
  vstupny bod a zdroj informacii pre vsetkych zamestnancov spolocnosti
- digitalizovat procesy, automatizovat a zefektivnit niektore manualne vykonavane cinnosti
- zefektivnit komunikaciu medzi oddeleniami a zvysit transparentnost v internych procesoch firmy
- merat realizovane vykony, vizualizovat ich a nasledne vyhodnocovat KPI
- vedeniu spolocnosti zjednodusit pristup k informaciam potrebnym k manazerskemu rozhodovaniu

### 02. Riesenie

V ramci pripravnej faze sme spolu s klientom absolvovali niekolko analytickych
workshopov a meetingov, vdaka ktorym sme detailne popisali a zakreslili sucasny
stav a zacali sme kreovat navrh buduceho riesenia, ktore spolocne stale vytvarame.

Vystupom bola podrobna analyza - funkcna a technicka specifikacia. Jej najvacsim
prinosom boli procesne diagramy, ktorymi sme klientovi vizualizovali aktualne
procesy prebiehajuce vo vyrobe v kontraste s navrhom vykonavania cinnosti
v Digitalnej platforme.

Projekt a jeho scope bol rozdeleny do viacerych priorit a faz, pricom v roku 2024
sme nastartovali implementaciu funkcionalit v ramci prveho balicka v1. V produkcii
zacal klient a jeho pracovnici Digitalnu platformu vyuzivat koncom 2024 a dennodenne
ju vyuzivaju pri svojej praci dodnes.

Funkcionality Digitalnej platformy v1:
- uvodny landing page s informaciami o plneni planu vyroby a planu trzieb
- CEO modul umoznujuci nastavovat cenu akcii/KPI vykonavanych vo vyrobe
- skenovanie prijmu tovaru na oddeleni logistiky a custom riesenie na tlac stitkov
  prostrednictvom printservera
- digitalizacia spracovania tovaru na notebookovom oddeleni
- digitalizacia spracovania tovaru na oddeleni renovacii a oprav s priamym
  napojenim na skladovu dostupnost nahradnych dielov v ERP systeme
- dashboardy/nastenky oddeleni s grafickou vizualizaciou vykonov jednotlivych
  zamestnancov ale aj oddeleni ako celku, statistiky spracovania objednavok/tovaru,
  reporty s vykonmi zamestnancov, podklady pre mzdy, plnenie obchodnych planov a pod.
- integracia na ERP system klienta: ziskavanie dat aj zapis dat
- sprava pouzivatelov a roli v Keycloak
- e-mailove notifikacie na pouzivatelov

Realizacia a technologicka implementacia bola koordinovana techleadom SCR, pricom
projekt vychadza z modernych open-source technologii bez akehokolvek vendor-lockingu.
Pouzite technologie: PHP, Vue, MySQL, Docker, Redis, RabbitMQ, Thumbor, S3 Storage,
Portainer, Keycloak, hosting v DigitalOcean cloud providerovi, Cypress pre
zabezpecenie automatizovanych testov.

### 03. Vysledok

Krok po kroku sme zdigitalizovali core procesy vo vyrobe od prijmu tovaru,
oddelenia logistiky, notebookoveho oddelenia az po ukoncenie renovacie produktu
na oddeleni renovacii a oprav.

Spolocnym usilim klienta a teamu SCR sa podarilo odstranit mnozstvo zbytocnej
prace, zefektivnit tazkopadne procesy a spristupnit potrebne informacie tak
vedeniu spolocnosti, ako aj vsetkym zamestnancom. Nahradili sme povodne vyuzivane
excel tabulky, komplikovanu tlac stitkov, manualne kopirovanie hodnot do ERP
systemu, zdielanie excelov medzi oddeleniami, rucne vypisovane papieriky nalepene
po produktoch, nevedomost o tom aky notebook je zrenovovatelny a ci su k nemu
dostupne nahradne diely, nevedomost ako sa dari firme v oblasti trzieb, vyroby
a pod. Okrem toho sme zabezpecili rychlo dostupne a transparentne informacie na
jednom mieste, ktore klient vyuziva k planovaniu kapacit, k odmenovaniu svojich
zamestnancov na zaklade vykonu, co prinasa zvysenie motivacie zamestnancov,
narast produktivity prace a kapacity samotnej vyroby.

Vyvoj aktualne pokracuje implementaciou dalsich funkcionalit, zapajania dalsich
oddeleni klienta do DP v ramci zadefinovaneho scopu projektu pre v2.

### Cislo od klienta (interny prinos, priamo od Maty)

Vdaka automatizacii a digitalizacii procesov firma nepotrebovala obsadit / uvolnila
5 pracovnych pozicii. V nakladoch to robi cca 15-tis. EUR mesacne, teda cca 200-tis.
EUR rocne uspory.
→ **POZOR na formulaciu v case study:** hovorit o efektivite/uspore nakladov vdaka
automatizacii, nie priamo o prepusteni ludi (citlivá HR tema, formulovat profesionalne
a takticky, ale cislo 200-tis. EUR/rok pouzit ako hlavny hrdinsky vysledok).

---

## Dohladane cisla o firme MBTECH / Techsavers / Refurbished.sk (overene z internetu)

> MBTECH BB s.r.o. je materska firma, ktora prevadzkuje znacky Techsavers a
> Refurbished.sk (predaj/velkoobchod repasovanej vypoctovej techniky).

**Financne udaje (Finstat, IČO 36622524):**
- Trzby: 14 008 377 EUR
- Zisk: 62 045 EUR
- Aktiva: 5 060 280 EUR
- Pocet zamestnancov: 50-99 (Finstat rozsah)
- Sidlo: Priemyselna ulica 15449/2, 974 01 Banska Bystrica
Zdroj: finstat.sk/36622524

**Firemne fakty (techsavers.sk/pages/o-nas, priamy fetch):**
- Zalozene v Banskej Bystrici, pocas viac ako 20 rokov (od 2003)
- Dnes posobia v 5 krajinach: Slovensko, Cesko, Polsko, Madarsko, Chorvatsko
- **410 000+** spokojnych zakaznikov
- **429 600+** repasovanych zariadeni spracovanych doteraz
- **98 %** miera spokojnosti zakaznikov
- cca **200 kusov denne** repasovanych
- 2-rocna zaruka (predlzitelna), zaruka na vydrz batérie
- Certifikacie: ISO 9001, ISO 14001, ISO 45001, Sewa enviro (2025), Green certifikat
  za recyklaciu elektroodpadu (2024)
- Popisuju sa ako "vobec prvé renovačné centrum výpočtovej techniky v strednej
  Európe" (nepouzivat "najvacsi" — to bolo len z nepriamej citacie vo webovom
  vyhladavani, nepotvrdene priamym zdrojom; "prve" JE priamo z ich vlastnej stranky)

**Zdroje:**
- https://www.finstat.sk/36622524
- https://techsavers.sk/pages/o-nas
- https://www.scrtechnologies.sk/case-study/mb-tech-digital-platform/
- https://www.scrtechnologies.sk/case-studies/
