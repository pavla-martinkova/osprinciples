[Otevřený přístup k publikacím](/osprinciples/open-access) | [Správa výzkumných dat](/osprinciples/sprava-dat) | [Další postupy otevřené vědy](/osprinciples/dalsi-postupy) 

# Správa výzkumných dat

Nakládání s daty je popsáno v projektovém plánu správy dat (Data Management Plan, DMP).

[Plán správy dat na Zenodo](https://zenodo.org/records/16419711)

## Jak nakládat s daty v průběhu projektu

Tak, aby byla srozumitelná a dostupná i v případě odchodu klíčových pracovnic\*ků projektu a jiných nečekaných událostech.

- Konzistentní pojmenovávání souborů a složek.
- Využívání bezpečných uložišť a zálohování, aby byla data uložena alespoň na dvou místech.
- Udržování dokumentace, aby bylo jasné například co znamenají názvy sloupců v tabulce nebo použité zkratky.

Při znovupoužití dat je potřeba dokumentovat filtrování nebo výběr, pokud nebude využit kompletní dataset.

## Jaká data je potřeba zveřejňovat

- Podkladová data k recenzovaným publikacím vzniklým v rámci projektu.
- Data spjatá s dalšími (nepublikačními) výsledky.
- Data, která nejsou spjatá s konkrétním výsledkem, ale mohou být využitelná mimo projekt.

V odůvodněných případech je možné ponechat data uzavřená, zpřístupnit je na vyžádání, nebo se zpožděním. Vždy musí být zveřejněna metadata.

<details markdown="1"> 
  <summary>Oprávněné důvody pro nezveřejnění dat</summary>

- Právo na ochranu soukromí
- Ochrana osobních údajů
- Důvěrnost údajů a dat
- Oprávněné obchodní zájmy, obchodní tajemství
- Práva duševního vlastnictví třetích stran
- Rozpor s oprávněnými zájmy příjemce, včetně komerčního využití dat
- Jiné oprávněné zájmy a oprávněná omezení

</details>

## Kde zveřejnit výzkumná data

Data musí být zveřejněna v důvěryhodném repozitáři. Nestačí platforma vydavatele (supplement u článku), ani v případě, že má dataset takto přidělené DOI. 

- [re3data.org](https://www.re3data.org/): rejstřík datových repozitářů s možností vyhledávání a filtrování

<details markdown="1"> 
<summary>Obecné důvěryhodné repozitáře</summary>

- [Zenodo](https://zenodo.org/) spravuje CERN
  - Komunita projektu, ke které lze výstupy přiřadit: [zenodo.org/communities/langinlife](https://zenodo.org/communities/langinlife)
- [Figshare](https://figshare.com/) spravuje Digital Science Company
- [Dataverse](https://dataverse.org/) spravuje Harvard
- [Národní datový repozitář](https://data.narodni-repozitar.cz/) spravuje CESNET

</details>

<details markdown="1">
<summary>Co musí splňovat zveřejněná výzkumná data ✅</summary>

- Neobsahují citlivé nebo osobní údaje v neanonymizované podobě.
- Mají přidělen persistentní identifikátor (DOI, Handle).
- Jsou uložena v důvěryhodném repozitáři pod jasně uvedenou licencí (CC 0, CC BY 4.0).
- Jsou uložena ve vhodném formátu: - [Přehledová tabulka vhodných formátů podle typu dat (UK Data Service)](https://ukdataservice.ac.uk/learning-hub/research-data-management/format-your-data/recommended-formats)
- Jsou popsána bohatými metadaty.
- Metadata jsou dostupná ve strojově čitelné podobě.
- Pokud jde o podkladová data k publikaci, jsou s ní pomocí metadat propojena.

</details>

## Jaká poskytnout metadata k datovým sadám

Na základě [Obecných doporučení pro metadatový popis výsledků výzkumu](https://doi.org/10.48813/yt6w-6h15) je potřeba uvést následující metadata.
- Název datové sady, srozumitelný sám o sobě (ne Data k článku)
- Celá jména původců (autorů a přispěvatelů) a jejich trvalý identifikátor (ORCID)
- Datum (plánovaného, v případě embarga) zveřejnění
- Vydavatel a jeho trvalý identifikátor (ROR)
- Srozumitelný popis datové sady
- Informace o dostupnosti dat (časové embargo, licence a další údaje)
- Trvalé identifikátory datové sady
- Informace o financování (poskytovatel financí a číslo projektu)
- Zařazení do vědní klasifikace podle oborů
- Klíčová slova

<details markdown="1"> 
<summary>Relevantní metadatové standardy</summary>

- [Brain Imaging Data Structure](https://bids.neuroimaging.io/) (BIDS)
- [Component Metadata Specification](https://fairsharing.org/FAIRsharing.2e0599) (CMDI)
- [Investigation Description Format](https://fairsharing.org/FAIRsharing.438d45) (IDF)
- [Linguistic Annotation Format](https://fairsharing.org/FAIRsharing.3cfa81) (LAF)
- [Minimum Information about an fMRI Study](https://fairsharing.org/10.25504/FAIRsharing.s3swh2) (MIfMRI)
- [Open Language Archives Community Metadata](https://fairsharing.org/FAIRsharing.17fbae) (OLAC Metadata)

</details>

## FAIR principy

- **F**indable – Data jsou nalezitelná lidmi i stroji díky popisným metadatům a persistentním identifikátorům.
- **A**ccessible – Data jsou dostupná díky důvěryhodným repozitářům.
- **I**nteroperable – Data jsou interoperabilní díky otevřeným formátům a používání standardů.
- **R**eusable – Data jsou opětovně využitelná díky poskytnutí kontextu pomocí metadat a dokumentace.

FAIR principy přibližuje dokument [Jak FAIR jsou vaše výzkumná data](https://zenodo.org/records/3739188)

- [fairsharing.org](https://fairsharing.org/): databáze standardů, formátů a dalších zdrojů pro FAIR data

---

[⬅ Otevřený přístup k publikacím](/osprinciples/open-access) | [Další postupy otevřené vědy ➡](/osprinciples/dalsi-postupy) 

Texty vznikly na základě příručky Metodika pro Open Science [projektu RES-HUM](https://reshum.muni.cz).

This site was built using [GitHub Pages](https://pages.github.com/).

[Otevřená věda v projektu LangInLife](https://pavla-martinkova.github.io/osprinciples/) © 2025 by [Pavla Martinková](https://github.com/pavla-martinkova) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).