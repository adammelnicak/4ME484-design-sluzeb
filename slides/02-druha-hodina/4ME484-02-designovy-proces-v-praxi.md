# 02 — Designový proces v praxi

**4ME484 · Design služeb · 5. 10. 2026**

[Vizuální prezentace v PDF](4ME484-02-designovy-proces-v-praxi.pdf)

Textová verze 56 snímků, exportovaná 4. 10. 2026. Číslo sekce odpovídá stránce PDF. Text vychází z aktuální prezentace; rozložení tabulek a vztahy v diagramech jsou převedeny do čitelné podoby. Odstavce označené „Popis vizuálu“ doplňují význam grafiky. Živé demonstrace nejsou v exportu zachyceny.

Pro práci s AI: odkazujte na čísla snímků, rozlišujte tvrzení, domněnky a otevřené otázky uvedené v prezentaci. Případová studie popisuje konkrétní projekt; nepovažujte její postup automaticky za povinnou strukturu svého projektu.

## Obsah

- [Úvod](#snimek-01) · snímky 01–02
- [Případová studie Orbiso](#snimek-03) · snímky 03–35
- [Metody a nástroje](#snimek-36) · snímky 36–47
- [Praktická část](#snimek-48) · snímky 48–56

<a id="snimek-01"></a>

## Snímek 01 — Designový proces v praxi

**2.** Případová studie Orbiso · Double Diamond · Git a repozitář stakeholdeři · představení služeb

<a id="snimek-02"></a>

## Snímek 02 — Kudy dnes půjdeme

I

**PŘÍPADOVÁ STUDIE ORBISO**

Co je Orbiso a proč vzniklo Kdo za ním stojí a na čem stojí Monorepo projektu Funkce od výzkumu k zadání

II

**METODY A NÁSTROJE**

Design thinking a Double Diamond Kde v procesu jste vy Git a GitHub Návrh vašeho repozitáře

**III**

**PRAKTICKÁ ČÁST**

Stakeholdeři a první rozhovor Práce v týmech Představení služeb Co si zařídíte do 12. 10.

<a id="snimek-03"></a>

## Snímek 03 — Část I · Případová studie Orbiso

I

Případová studie Orbiso

Co je Orbiso, proč vzniklo, kdo za ním stojí, jak držíme práci a jak jedna funkce prošla od výzkumu k zadání.

<a id="snimek-04"></a>

## Snímek 04 — Co je Orbiso

Platforma, která převádí odbornou péči a edukaci do digitálních programů pro každodenní použití.

**ODBORNÍK**

Přinese odborný obsah a sestaví z něj program bez nutnosti rozumět programování/vývoji digitálních intervencí.

**UŽIVATEL**

Prochází program v aplikaci krok za krokem, obvykle na doporučení odborníka.

<a id="snimek-05"></a>

## Snímek 05 — Co je digitální intervence

Zařízení a programy, které pomocí digitální technologie podněcují nebo podporují změnu chování.

Michie et al., 2017 · Journal of Medical Internet Research

**KOUŘENÍ**

Aplikace s denními úkoly a záznamem chuti na cigaretu.

**NESPAVOST**

Online kurz se spánkovým deníkem a postupnými kroky.

**LÉKY**

SMS připomínky, které pomáhají brát léky pravidelně.

**STRES**

Krátká denní cvičení zvládání stresu v telefonu.

Cílem není technologie, ale to, co člověk začne dělat jinak.

<a id="snimek-06"></a>

## Snímek 06 — Co je digitální program

Jedna z podob digitální intervence: obsah rozložený do kroků v čase, kterými člověk prochází.

**JEDNORÁZOVÁ INFORMACE**

Leták, článek nebo e-mail. Člověk ho jednou přečte a tím to končí.

**DIGITÁLNÍ PROGRAM**

Vede člověka několik týdnů. Každý krok má svůj účel.

**1.** Text nebo video

**2.** Úkol na doma

**3.** Krátký dotazník

**4.** Připomínka a další krok

<a id="snimek-07"></a>

## Snímek 07 — Dva pohledy na digitální intervence

| Hledisko | Digital health | HCI (FIS friendly) |
| --- | --- | --- |
| HLAVNÍ OTÁZKA | Funguje to? Zlepší se zdraví? | Jak s tím lidé pracují a proč? |
| CO SE CENÍ | Systematičnost, teorie změny chování, klinická relevance | Novost, poznání o interakci, reflexe návrhu |
| KDY TO „FUNGUJE“ | Když se zlepší výsledek | Když mechanismus dělá, co má |
| TYPICKÉ METODY | Randomizované studie, systematické přehledy | Kvalitativní studie, prototypy, nasazení v terénu |
| KDE PUBLIKUJE | JMIR, Internet Interventions | CHI, NordiCHI, ACM Digital Library |

**MERGE:** Od roku 2026 pořádá SIGCHI samostatnou konferenci ACM Interactive Health.

<a id="snimek-08"></a>

## Snímek 08 — Výchozí projekt: MindCare

**01.** Mobilní aplikace na podporu duševního zdraví onkologických pacientů (Masarykův onkologický ústav, LF MU).

**02.** Tři osmitýdenní digitální programy a dvě randomizované kontrolované studie (grant AZV ČR).

**03.** Zjištění: obsah postavit jde. Zakázkový vývoj aplikace je ale drahý a iterace dlouhé.

Zkušenost z MindCare nás přímo přivedla k Orbisu.

<a id="snimek-09"></a>

## Snímek 09 — Jaký problém Orbiso řeší

**DNES**

Odborníci předávají doporučení e-mailem, letákem nebo jednorázovou instrukcí.

Pro každý program by museli stavět novou aplikaci.

**ORBISO**

Jedna platforma pro mnoho programů.

Odborník program sestaví sám, bez vývoje nové aplikace.

**PREMISA**

Uživatel přichází na doporučení odborníka. Důvěra k odborníkovi nese důvěru k obsahu.

<a id="snimek-10"></a>

## Snímek 10 — Životní cyklus programu

**1.** Návrh ve Wizardu

ze záměru odborníka připraví návrh, i s pomocí AI

**2.** Tvorba v Editoru

obsah, úkoly a dotazníky krok za krokem

**3.** Publikace a sdílení

program se zpřístupní uživatelům

**4.** Průchod programem v aplikaci

uživatel ho prochází v telefonu

**5.** Analýza a export dat

odborník vidí, jak program probíhá

Z analýzy se vracíme k návrhu. Program se postupně zlepšuje.

> **Popis vizuálu:** Diagram propojuje pět popsaných kroků do cyklu. Analýza a export dat vedou zpět k návrhu ve Wizardu.

<a id="snimek-11"></a>

## Snímek 11 — Tým a partneři

**S PODPOROU TA ČR**

Projekt běží v grantovém rámci s milníky a evaluací dopadu programů.

Produktový tým: vývoj a provoz platformy

Vedení

Produkt a design

Full-stack vývoj

Testování

5,5

člověka

Odborné týmy: obsah programů, metodika, výzkum

25+

odborníků z medicíny, psychologie a pedagogiky

> **Popis vizuálu:** Loga na snímku: Bindworks, Masarykova univerzita, Masarykův onkologický ústav a TA ČR. Ikony ilustrují produktový tým a širší skupinu odborníků.

<a id="snimek-12"></a>

## Snímek 12 — Programy v Orbisu

**MOÚ**

BRCAware

Informace a podpora pro nositele mutace BRCA

**MOÚ**

Paliativní péče pro pacienty

Podpora pacientů v paliativní péči

**LF MUNI**

Prodloužení života ve zdraví

Prevence souběžně s běžnou lékařskou péčí

+19

dalších programů od odborných týmů

orbiso.cz/programy

<a id="snimek-13"></a>

## Snímek 13 — Výchozí domněnka

**DOMNĚNKA**

„Lidé budou programy používat hlavně proto, že za nimi stojí lékaři a odborníci.“

**PROČ ZATÍM JEN DOMNĚNKA**

**01.** Takový nástroj tu zatím nikdo nesestavil. Není s čím srovnat.

**02.** Odborníci jsou náš výchozí bod, ne ověřený důvod, proč lidé program používají.

**03.** Potvrdit nebo vyvrátit ji může až skutečný provoz programů.

<a id="snimek-14"></a>

## Snímek 14 — Záměr máme. Byznys case hledáme

**CO MÁME**

Odborné týmy s obsahem a metodikou

Výzkumné projekty a granty

Programy v pilotním provozu

**CO HLEDÁME**

Kdo za program zaplatí, až grant skončí?

Pro koho je dost cenný, aby ho dlouhodobě provozoval?

Jak se program dostane k lidem, kteří ho potřebují?

<a id="snimek-15"></a>

## Snímek 15 — Kam projekt míří

**Q4/24**

Start projektu

**Q4/25**

Start vývoje

**Q3/26**

Wizard, Editor a aplikace

**Q4/26**

Pilotní programy

**Q1/27**

Komerční provoz

**JEDNOTLIVCI**

Odborník vytvoří první program a pošle ho odkazem pár lidem.

**TÝMY**

Provozují programy společně, ve vlastním vzhledu a s přehledem, jak jimi uživatelé procházejí.

**ORGANIZACE**

Nemocnice, fakulty nebo sítě pracovišť. Spuštění, výzkum i odborná spolupráce na míru.

**KOMU CHCEME ORBISO NABÍZET**

<a id="snimek-16"></a>

## Snímek 16 — A co kdyby to šlo i bez odborníka?

**DNES**

Program od odborníka

Odborník program navrhne a doporučí. Obsah nese jeho odbornost.

**OTEVŘENÁ MYŠLENKA**

Program, který si sestavím sám

Uživatel si program poskládá pro vlastní potřebu nebo problém s pomocí AI.

<a id="snimek-17"></a>

## Snímek 17 — Jak se díváte na digitální péči?

**01.** Co z péče o své zdraví a duševní pohodu si dokážete představit řešit online?

**02.** Co byste online řešit nechtěli, a proč?

**03.** Co rozhoduje o tom, jestli byste digitálnímu programu věřili?

**POSTUP**

Proberte to dve dvojici/trojici, pak nasdílíme společně.

<a id="snimek-18"></a>

## Snímek 18 — Co je monorepo

orbiso/

**PRODUKT**

Wizard a Editor

Aplikace

Backend

**PRÁCE KOLEM NĚJ**

Dokumentace

Výzkum

Zadání

**REPOZITÁŘ**

Společné úložiště souborů projektu s historií změn.

**MONOREPO**

Jeden repozitář pro více součástí produktu. V Orbisu i pro dokumentaci, výzkum a zadání.

> **Popis vizuálu:** Schéma řadí části produktu a práci kolem něj pod společný kořen orbiso/.

<a id="snimek-19"></a>

## Snímek 19 — Výhody monorepa

Dohledáme, z čeho zadání vychází.

Nový kolega hledá důvod rozhodnutí.

Propojíme změnu s dalšími částmi produktu.

Změna ve Wizardu ovlivní Editor.

Lidé i agenti vědí, kde hledat kontext.

Agent hledá konkrétní studii a aktuální zadání.

**PŘÍKLAD**

**PODMÍNKA**

Funguje to jen tehdy, když jsou podklady propojené a někdo je udržuje.

<a id="snimek-20"></a>

## Snímek 20 — Struktura repozitáře

orbiso/

**01.** ▸ docs/

Co stavíme a jak spolu pracujeme

**02.** ▸ research/

Co jsme zjistili od lidí

**03.** ▸ tasks/

Co chceme změnit a proč

**04.** ▸ wizard/ · builder/ · app/

Kde změna vzniká a ověřuje se

Wizard a Editor, aplikace pro uživatele, backend

<a id="snimek-21"></a>

## Snímek 21 — Jak udržujeme pořádek

Zadání a dokumentace se během týdne rozcházejí. Každý pátek je srovná agent.

**BĚHEM TÝDNE · 11. 9.**

Vývojář dokončí schvalování programů do knihovny.

Zadání i dokumentace pořád popisují starý stav.

**V PÁTEK · 18. 9. · AGENT**

Zadání označí jako hotové.

Dokumentaci doplní o novou funkci.

Roadmapu přepne na splněno.

**ČLOVĚK**

Nikdo to nepřepisuje ručně. Člověk změny jen zkontroluje a schválí.

<a id="snimek-22"></a>

## Snímek 22 — Co stavíme a jak spolu pracujeme

docs/

Co je Orbiso a komu slouží

Jak produkt funguje

Pravidla spolupráce a dokumentace

Dále: odborné články, ze kterých vycházíme · právní dokumenty · strategie a reporty

orbiso/

docs/

**● TEĎ**

popis a pravidla

research/

výzkum

tasks/

zadání

realizace

wizard · builder · app

**POZOR**

Popis funkcí odpovídá tomu, co opravdu existuje.

<a id="snimek-23"></a>

## Snímek 23 — Co jsme zjistili od lidí

research/

Hloubkové rozhovory: praxe a potřeby odborníků

Testování prototypu: průchod Wizardem

Persony: syntéza s pomocí AI

orbiso/

docs/

popis a pravidla

research/

**● TEĎ**

výzkum

tasks/

zadání

realizace

wizard · builder · app

<a id="snimek-24"></a>

## Snímek 24 — Co chceme změnit a proč

tasks/

Co a proč

Jak poznáme, že je hotovo a co otestovat

Návaznosti a otevřené otázky

orbiso/

docs/

popis a pravidla

research/

výzkum

tasks/

**● TEĎ**

zadání

realizace

wizard · builder · app

**POZOR**

Zadání popisuje, co má vzniknout. Neznamená, že to už existuje.

<a id="snimek-25"></a>

## Snímek 25 — Kde změna vzniká a ověřuje se

realizace

wizard/ · builder/ — autorské prostředí

app/ — aplikace pro uživatele

backend — práce s daty a operace na serveru

orbiso/

docs/

popis a pravidla

research/

výzkum

tasks/

zadání

realizace

**● TEĎ**

wizard · builder · app

**CYKLUS**

Zadání → realizace → ověření → aktualizovaný popis. Při problému zpět k zadání.

<a id="snimek-26"></a>

## Snímek 26 — Příklad: Wizard

**CO TO JE**

Průvodce, který autora provede od popisu problému k první struktuře programu. Tu pak dotváří v Editoru.

**PROČ HO STAVÍME**

Odborník má obsah, ale ne zkušenost s tvorbou digitálních programů. Wizard mu pomůže začít.

**PROČ PRÁVĚ ON**

Má nejúplnější stopu: výzkum, workshop s odbornými týmy, rozhodnutí i zadání.

<a id="snimek-27"></a>

## Snímek 27 — Jak Wizard vznikal

**MIRO!**

**01.** Životní cyklus digitální intervence

**02.** Rozkreslení autorského prostředí

**03.** Prototyp Wizardu

**04.** Testování s odborníky

**05.** Workshop: zpětná vazba a další kroky

**06.** Zadání změn do repozitáře

> **Popis vizuálu:** Snímek je rozcestník živé ukázky v Miru. Samotný průchod boardem není součástí tohoto exportu.

<a id="snimek-28"></a>

## Snímek 28 — Od záměru k zadání

Cesta jedné funkce repozitářem

**01.** Design brief

Návrh z interního workshopu a zkušeností týmu.

**02.** Výzkum s odborníky

13 rozhovorů a test prototypu: 23 sezení, 24 lidí.

**03.** Rozhodnutí & redesign

Další iterace Wizardu po zpětné vazbě.

**04.** Zadání vývoji

Co má vzniknout a jak poznáme, že je hotovo.

**05.** Po zadání

Vývoj, kontrola, test, aktualizace dokumentace.

Na jedné funkci ukážu, jak se z výzkumu stane zadání změny. Stejnou cestou půjdete vy.

docs/

research/

tasks/

tasks/

wizard/ + docs/

<a id="snimek-29"></a>

## Snímek 29 — Výchozí bod: design brief

**CO UŽ BYLO**

Návrh flow a obrazovek z interního workshopu.

**CO JSME JEŠTĚ NEVĚDĚLI**

Jak odborníci opravdu přemýšlejí nad tvorbou digitálních programů?

Zatím jen lidé z psychologie, psychiatrie a psychoterapie, ne laičtí autoři. Jak může pomoci AI, byla spíš návrhová otázka než výzkumná.

<a id="snimek-30"></a>

## Snímek 30 — Na co jsme se ptali

**VÝBĚR Z RESEARCH BRIEFU · 13 HLOUBKOVÝCH ROZHOVORŮ**

Jak dnes předávají podporu mezi setkáními?

Současné workflow, nástroje, obsah a překážky.

Proč by část podpory chtěli převést do digitálu?

Motivace, cíle a hranice toho, co má dělat člověk.

Kde chtějí zachovat vlastní rozhodování?

Tvorba obsahu, práce s AI, důvěra a odpovědnost.

**CÍL ROZHOVORŮ**

Porozumět praxi a formulovat hypotézy pro návrh Wizardu, ne potvrdit hotové UI.

<a id="snimek-31"></a>

## Snímek 31 — Co nám řekli odborníci

13 rozhovorů s lidmi z psychologie a psychiatrie. Víc než jen o Wizardu.

**DVA PŘÍSTUPY**

Struktura, nebo vztah

Strukturované přístupy (např. KBT) jdou digitalizovat snadno. Mnoho terapeutů ale pracuje procesně, přes vztah.

**MEZI SEZENÍMI**

Opora, ne úkoly

Klient má mezi sezeními dostat oporu, ne úkoly ke splnění. Tak to vidí 9 z 13.

**OTEVŘENÁ OTÁZKA**

Jak v digitálním programu pracovat s emocemi a vztahem? Zatím to máme v backlogu.

<a id="snimek-32"></a>

## Snímek 32 — Dvě metody výzkumu

Rozhovor ukáže praxi. Test ukáže konkrétní překážku

**13.** Explorativní rozhovory: jak odborníci tvoří obsah, mluví o své práci a vnímají AI.

**10.** Moderovaná sezení nad funkčním prototypem, který jsme sestavili s pomocí AI.

<a id="snimek-33"></a>

## Snímek 33 — Jak probíhá redesign

**ŽIVĚ · UKÁZKA**

Už nenavrhujeme ve Figmě. Návrh i prototyp vznikají blíž skutečnému produktu.

**01.** Návrh v Pen

Obrazovky navrhujeme v nástroji, se kterým umí pracovat i AI agent.

**02.** Prototyp na localhostu

Funkční prototyp běží přímo na počítači.

**03.** Se skutečnými daty

Lokální backend s ukázkovými programy (OrbStack).

**VÝSLEDEK**

Rozhodnutí z prototypu se přepíšou do zadání pro vývoj + občas včetně samotného prototypu

> **Popis vizuálu:** Snímek uvádí živou ukázku redesignu. Průchod návrhem, lokálním prototypem a backendem není součástí tohoto exportu.

<a id="snimek-34"></a>

## Snímek 34 — Zadání a prototyp jako podklad pro vývoj

**PR OD PRODUKTU**

**ZADÁNÍ**

Co a proč

Kdy je hotovo.

+

**PROTOTYP**

Jak to vypadá

A jak se to chová.

**PR OD VÝVOJE**

**KÓD**

Funkce

V menších částech. U Wizardu třeba sedm.

**PRAVIDLO VS. PRAXE**

Pravidlo říká: dokumentace před sloučením. V praxi ji často dorovná až páteční revize.

> **Popis vizuálu:** Schéma: pull request od produktu obsahuje zadání a prototyp; navazují menší pull requesty od vývoje s implementací.

<a id="snimek-35"></a>

## Snímek 35 — Od zadání do produkce

**1.** Zadání

produkt a design

**2.** Vývoj

vývojář

**3.** Code review

druhý vývojář

**4.** Dev prostředí

vývoj nasadí

**5.** Testování

tester

**6.** Dokumentace

páteční revize

**7.** Produkce

tým vydá

**KDO TO HLÍDÁ**

Páteční agent srovná zadání a dokumentaci se skutečností.

**KDO KROK DĚLÁ**

Najde tester chybu? Zpět do vývoje, případně až k zadání.

> **Popis vizuálu:** Šipky spojují kroky od zadání do produkce. Z testování vede návrat při chybě zpět do vývoje, případně k zadání.

<a id="snimek-36"></a>

## Snímek 36 — Část II · Metody a nástroje

II

Metody a nástroje

Design thinking, Double Diamond, Git a návrh vašeho repozitáře.

<a id="snimek-37"></a>

## Snímek 37 — Design thinking

Zdroj: Stanford d.school, Design Thinking Bootleg.

Přístup, který staví na porozumění lidem, hledání možností a ověřování návrhů.

Empathize

pochopit lidi

Define

pojmenovat problém

Ideate

hledat nápady

Prototype

zhmotnit nápad

Test

ověřit u lidí

> **Popis vizuálu:** Pět šestiúhelníků zobrazuje Empathize → Define → Ideate → Prototype → Test.

<a id="snimek-38"></a>

## Snímek 38 — Double Diamond

**SPRÁVNÝ PROBLÉM**

**SPRÁVNÉ ŘEŠENÍ**

Discover

Define

Develop

Deliver

Zdroj: Design Council, Double Diamond (2004); Framework for Innovation (2019).

Nejdřív hledáme správný problém, pak správné řešení.

> **Popis vizuálu:** Dva diamanty znázorňují rozšiřování a zužování možností: Discover → Define hledá správný problém; Develop → Deliver hledá správné řešení.

<a id="snimek-39"></a>

## Snímek 39 — Každá fáze odpovídá na jinou otázku

| Fáze | Otázka |
| --- | --- |
| 01 · Discover | „Co se ve službě / mimo službu skutečně děje?“ |
| 02 · Define | „Který problém stojí za řešení?“ |
| 03 · Develop | „Jaká řešení připadají v úvahu?“ |
| 04 · Deliver | „Které z nich opravdu funguje?“ |

<a id="snimek-40"></a>

## Snímek 40 — Naše kroky z první hodiny v téže mapě

Discover

Define

Develop

Deliver

**01.** Vymezit

Službu a nejistotu

**02.** Porozumět

Podklady a fungování

**03 · NA HRANĚ**

Rozhodnout

Patří do obou diamantů

**04.** Vytvořit a ověřit

Funkční podoba a jak funguje

**05.** Obhájit

Mimo mapu: specifikum kurzu

Diamant vysvětluje logiku. Pět kroků je váš pracovní plán.

> **Popis vizuálu:** Kroky Vymezit a Porozumět jsou pod prvním diamantem; Rozhodnout na hranici obou; Vytvořit a ověřit pod druhým. Obhájit stojí mimo diamanty jako požadavek kurzu.

<a id="snimek-41"></a>

## Snímek 41 — Mapa není trať

Fáze ≠ povinné metody.

Metody volíte podle toho, co potřebujete zjistit.

Jeden rozhovor ≠ potřeby uživatelů.

Rozhovor se zadavatelem první diamant otevírá, nezavírá.

Návrat ≠ selhání.

Test Wizardu nás vrátil k návrhu. Byl to užitečný výsledek.

**100METOD.CZ**

Rozcestník metod pro design služeb (KISK FF MU)

<a id="snimek-42"></a>

## Snímek 42 — Kde jste teď vy?

Discover

Define

Develop

Deliver

**VY JSTE TADY**

**SEM SE DOSTANETE POZDĚJI**

**VAŠE SMĚRY**

Jsou to nápady na řešení, tedy druhý diamant. Teď z nich udělejte otázky, které v prvním ověříte.

**CHECK 12. 10.**

Nechci hotový výzkum. Chceme vědět, co v prvním diamantu hledáte.

> **Popis vizuálu:** Značka „Vy jste tady“ je na začátku Discover. Druhý diamant je zesvětlený a označený jako pozdější fáze.

<a id="snimek-43"></a>

## Snímek 43 — Git a GitHub bez slangu

**GIT**

Historie změn projektu. U každé uložené změny víte co, kdo a kdy.

změna 1

změna 2

změna 3

**U ZMĚNY 3: KDO · KDY · CO**

**GITHUB**

Místo, kde repozitář sdílíte s týmem a se mnou.

tým

vy

já

repozitář

**PRVNÍ ÚČET?**

Úplně v pořádku. Kurz není výukou Gitu. Stačí, když víte, kam co uložit a jak to sdílet.

> **Popis vizuálu:** Git je zobrazen jako historie tří změn; GitHub jako společný repozitář, do něhož směřují tým, student a vyučující.

<a id="snimek-44"></a>

## Snímek 44 — Slovník vám vysvětlí agent

**TŘEBA TAKHLE**

„Co znamená, že mi Git hlásí konflikt?“

„Jak uložím svoje změny a pošlu je týmu?“

„Co se v repozitáři změnilo od včerejška?“

„Ulož moje změny s popisem a pošli je týmu.“

**POJISTKA**

Agent vám Git vysvětlí i provede.

Než potvrdíte příkaz, který něco maže nebo přepisuje, zeptejte se, co přesně udělá.

Za výsledek odpovídáte vy.

**NIKDY**

Do repa nepatří jména respondentů, kontakty, souhlasy ani nahrávky.

<a id="snimek-45"></a>

## Snímek 45 — Na repo se můžete dívat různě

Cursor

editor s agentem

Antigravity

editor s agentem

VS Code

klasický editor

GitHub na webu

bez instalace, v prohlížeči

**UKÁZKA**

> **Popis vizuálu:** Screenshot editoru Cursor ukazuje strom souborů kurzového repozitáře a otevřený náhled README.md. Demonstruje práci se stejným repozitářem v editoru; neobsahuje další zadání.

<a id="snimek-46"></a>

## Snímek 46 — Vaše mapa a dohoda

Zapište obojí do README a udělejte první commit.

**MAPA PROJEKTU**

Jakými kroky asi projdete?

Co v kterém kroku vznikne?

Kde čekáte největší nejistotu?

**TÝMOVÁ DOHODA**

Kdo se v týmu stará o co?

Kde se domlouváte a v jakých nástrojích pracujete?

**10.** minut v týmech.  Dohodu dokončíte do 12. 10.

<a id="snimek-47"></a>

## Snímek 47 — Co může v kterém kroku vzniknout

| FÁZE | CO V NÍ MŮŽE VZNIKNOUT | NÁSTROJE, NAPŘÍKLAD |
| --- | --- | --- |
| Discover | průchod službou, zápisy z rozhovorů, podklady od stakeholderů | Miro, poznámky, přepis rozhovorů |
| Define | tvrzení k ověření, vymezení problému, rozhodnutí | Miro, FigJam |
| Develop | zvažované varianty, zadání změny | Figma, Pen |
| Deliver | prototyp, ověření, omezení | Figma, Pen, Cursor |
| Napříč | kdo co udělal, otevřené otázky | GitHub, Cursor, Teams |

<a id="snimek-48"></a>

## Snímek 48 — Část III · Praktická část

**III**

Praktická část

Stakeholdeři, první rozhovor a představení služeb.

<a id="snimek-49"></a>

## Snímek 49 — Kdo všechno do služby zasahuje

Nejcennější pohled často nemá ten, koho napadne první.

**PŘÍKLAD Z PLÁNOVÁNÍ MĚSTA**

Když si udělali mapu aktérů, nejcennějším se ukázal pošťák.

Chodí čtvrtí každý den a vidí ji skrz naskrz.

**SLUŽBA**

Pacient

Lékař

Sestra

Správa obsahu

Rodina

ovlivní, jestli léčbu dodržuje

Vedení

Plátce

Další lékaři

**PRO VÁŠ PROJEKT**

Kdo ve vaší službě vidí věci, které ostatní nevidí?

> **Popis vizuálu:** Mapa soustředí aktéry kolem služby. Rodina je zvýrazněná jako aktér ovlivňující dodržování léčby.

<a id="snimek-50"></a>

## Snímek 50 — K čemu je první setkání?

**ANO**

Porozumět službě a jejímu zázemí

Zjistit omezení a co je pro ně úspěch

Dozvědět se, s kým případně mluvit dál

NE

Prodat svůj nápad

Sbírat přání na funkce

Potvrdit si zvolené řešení

<a id="snimek-51"></a>

## Snímek 51 — Příprava prvního rozhovoru

Takhle si připravíte první rozhovor.

**01.** Co potřebujeme zjistit

cíle rozhovoru z vašich směrů

**02.** Kdo k tomu může mluvit

aktéři a perspektiva kontaktu

**03.** Na co se zeptáme

zkušenosti, podklady, očekávání

**04.** Co si domluvíme

přístupy, další kontakty, jak navážeme

<a id="snimek-52"></a>

## Snímek 52 — Ptejte se na zkušenosti, podklady a očekávání

| Účel | Otázka | Upřesnění |
| --- | --- | --- |
| Nenabízet řešení | „Popište poslední situaci, kdy jste řešili, zda lidé službu dál používají.“ | Místo: „Nechtěli byste, aby aplikace posílala připomínky?“ |
| Doptat se na podklady | „Co považujete za hlavní problém? Z čeho vycházíte? Můžete popsat konkrétní případ?“ | Otázka na problém je v pořádku. Důležité je doptat se, z čeho odpověď vychází. |
| Vyjasnit úspěch | „Podle čeho za půl roku poznáte, že změna pomohla?“ | Na omezení se zeptejte zvlášť: „Co by mohlo zavedení změny zkomplikovat?“ |

<a id="snimek-53"></a>

## Snímek 53 — Co vám řekne a čím je to podložené?

**PŘÁNÍ NEBO ZADÁNÍ**

Co chce.

„Chceme, aby pacienti portál používali víc.“

**KONKRÉTNÍ ZKUŠENOST**

Případ, který viděl nebo zažil.

„Minulý týden se mě pacientka po propuštění ptala…“

**VYSVĚTLENÍ NEBO ZOBECNĚNÍ**

Proč to tak podle něj je.

„Nečtou to, protože je to dlouhé.“ „Většina si to hledá na internetu.“

**U KAŽDÉ VÝPOVĚDI**

Kdo to říká? Z čeho vychází? Co ještě potřebujeme ověřit?

<a id="snimek-54"></a>

## Snímek 54 — Dolaďte představení služby

**01.** Co jste prošli a zjistili

**02.** Co zatím předpokládáte

**03.** Jaké směry zvažujete

**04.** Koho se potřebujete zeptat a na co

kdo do služby zasahuje · 2–3 cíle rozhovoru

**05.** Co už máte domluvené a co ještě chybí

**POKYN**

Navažte na domácí přípravu. Domluvte se, kdo co řekne.

Osnova vašeho představení: 4 minuty, pět bodů.

**10.** minut v týmech

<a id="snimek-55"></a>

## Snímek 55 — Představení týmů

**4.** minuty na tým

Jak vidíte svou službu? Podle osnovy, kterou jste si připravili.

<a id="snimek-56"></a>

## Snímek 56 — Další krok: rozhovor se stakeholderem

Do 12. 10. dolaďte otázky, na které se chcete zeptat.

**01 · JÁ**

Propojím vás

Během týdne vás se stakeholderem propojím.

**02 · VY**

Dolaďte otázky

Ptejte se na zkušenosti, podklady a očekávání (snímek 52).

**03 · VY**

Uložte je do repa

Hotový rozhovor do checku nečekáme.

**CHECK 12. 10.**

Společně projdeme cíl a směr vašeho rozhovoru se stakeholderem.
