[Home](/osprinciples/) | [Otevřený přístup k publikacím](/osprinciples/open-access) | [Správa výzkumných dat](/osprinciples/sprava-dat) | [Další postupy otevřené vědy](/osprinciples/dalsi-postupy) 

## Správa výzkumných dat

Nakládání s daty je popsáno v projektovém plánu správy dat (Data Management Plan, DMP).

[Plán správy dat na Zenodo](...)

### Jak nakládat s daty v průběhu projektu

- Využívání bezpečných uložišť a zálohování.
- Standardizované pojmenovávání souborů.

### Jaká data je potřeba zveřejňovat

Povinné zveřejnění se týká:
- podkladových dat k recenzovaným publikacím vzniklým v rámci projektu
- dat spjatých s dalšími (nepublikačními) výsledky
- dat, která nejsou spjatá s konkrétním výsledkem, ale mohou být využitelná mimo projekt

V odůvodněných případech je možné ponechat data uzavřená, zpřístupnit je na vyžádání, nebo se zpožděním. Vždy musí být zveřejněna metadata.

<details markdown="1"> 

<summary>Mezi oprávněné důvody pro nezveřejnění dat patří:</summary>

- právo na ochranu soukromí
- ochrana osobních údajů
- důvěrnost dat
- oprávněné obchodní zájmy, obchodní tajemství
- práva duševního vlastnictví třetích stran
- rozpor s oprávněnými zájmy příjemce, včetně komerčního využití dat

</details>

### FAIR principy

Výzkumná data mají být:
- **F**indable <br>nalezitelná lidmi i stroji díky popisným metadatům a persistentním identifikátorům
- **A**ccessible <br> dostupná díky důvěryhodným repozitářům
- **I**nteroperable <br> interoperabilní díky otevřeným formátům a používání standardů
- **R**eusable <br> opětovně využitelná díky poskytnutí kontextu pomocí metadat a dokumentace

FAIR principy přibližuje dokument [Jak FAIR jsou vaše výzkumná data](https://zenodo.org/records/3739188)

<details markdown="1"> 
<summary>Relevantní metadatové standardy</summary>

- [Brain Imaging Data Structure](https://bids.neuroimaging.io/) (BIDS)
- [Component Metadata Specification](https://fairsharing.org/FAIRsharing.2e0599) (CMDI)
- [Investigation Description Format](https://fairsharing.org/FAIRsharing.438d45) (IDF)
- [Linguistic Annotation Format](https://fairsharing.org/FAIRsharing.3cfa81) (LAF)
- [Minimum Information about an fMRI Study](https://fairsharing.org/10.25504/FAIRsharing.s3swh2) (MIfMRI)
- [Open Language Archives Community Metadata](https://fairsharing.org/FAIRsharing.17fbae) (OLAC Metadata)
- [fairsharing.org](https://fairsharing.org/): databáze standardů, formátů a dalších zdrojů pro FAIR data

</details>

- [re3data.org](https://www.re3data.org/): rejstřík datových repozitářů s možností vyhledávání a filtrování
- [Přehledová tabulka podle typu dat (UK Data Service)](https://ukdataservice.ac.uk/learning-hub/research-data-management/format-your-data/recommended-formats)

<details markdown="1"> 
<summary>Relevantní důvěryhodné repozitáře</summary>

- [Zenodo](https://zenodo.org/): obecný repozitář, spravuje CERN
  - výstupy lze přidat ke komunitě projektu: [zenodo.org/communities/langinlife](https://zenodo.org/communities/langinlife)
- [Figshare](https://figshare.com/): obecný repozitář, spravuje Digital Science Company
- [Dataverse](https://dataverse.org/): obecný repozitář, spravuje Harvard
- [Národní datový repozitář](https://data.narodni-repozitar.cz/): český obecný repozitář, spravuje CESNET

</details>

<details markdown="1">
<summary>Co musí splňovat zveřejněná výzkumná data ✅</summary>

- neobsahují citlivé nebo osobní údaje v neanonymizované podobě
- mají přidělen persistentní identifikátor (DOI, Handle)
- jsou uložena v důvěryhodném repozitáři pod jasně uvedenou licencí (CC 0, CC BY 4.0)
- jsou uložena ve vhodném formátu
- jsou popsána bohatými metadaty
- metadata jsou dostupná ve strojově čitelné podobě
- pokud jde o podkladová data k publikaci, jsou s ní pomocí metadat propojena

</details>

---

Texty vznikly na základě příručky Metodika pro Open Science [projektu RES-HUM](https://reshum.muni.cz).

This site was built using [GitHub Pages](https://pages.github.com/).