[Home](/osprinciples/index-en) | [Open Access to publications](/osprinciples/open-access-en) | [Research data management](/osprinciples/sprava-dat-en) | [Other open science practices](/osprinciples/dalsi-postupy-en) | [ČEŠTINA 🇨🇿](/osprinciples/sprava-dat) |

# Research data management

Data management is described in detail in the project's Data Management Plan.

- [Data Management Plan on Zenodo](https://doi.org/10.5281/zenodo.16419710)

## How to handle data during the project

So that it remains understandable and accessible even in case of departure of key project members or other unexpected events.

- Consistent naming of files and folders.
- Secure storage and backup to ensure that data is stored in at least two locations.
  - [Recommendations for the usage of storages](https://it.muni.cz/en/overviews/recommendations-for-the-usage-of-storages) for MU, but categorisation of data useful for everyone
  - [OwnCloud](https://www.cesnet.cz/en/services/data-storage-3/owncloud-16) storage from CESNET, 100 GB (and more upon request)
- Sufficient documentation to clarify, for example, the meaning of column names in tables or abbreviations used.
- When reusing data, it is necessary to document filtering or selection if the complete dataset is not used.

## Which data needs to be open

- Data supporting peer-reviewed publications produced within the project.
- Data associated with other (non-publication) results.
- Data that are not associated with a specific result but may be usable outside the project.

In justified cases, data may be kept closed, made available on request or after an embargo period. Metadata must always be published. 

<details markdown="1"> 
  <summary>Legitimate reasons for non-disclosure</summary>

- Right to privacy
- Data protection and confidentiality
- Legitimate business interests, trade secrets
- Third party intellectual property rights
- Conflict with legitimate interests of the recipient, including commercial exploitation of the data 
- Other legitimate interests and restrictions 

</details>

## Where and how to publish research data
Do not hesitate to contact OS support for more information.

Data needs to be published in a trusted repository. The publisher's platform (data supplement) is not sufficient, even if DOI has been assigned this way.

Data needs to be stored in a suitable format and adequately described by metadata, ideally in accordance with standards. Adequate documentation will ensure that data is comprehensible for re-users.

- [File formats recommended by the UK Data Service](https://ukdataservice.ac.uk/learning-hub/research-data-management/format-your-data/recommended-formats)
- [FAIRsharing.org](https://fairsharing.org/): database of standards, formats, and other resources for FAIR data

### Recommended trusted repositorie
- [re3data.org](https://www.re3data.org/): data repositories registry with search and filter options
- [LINDAT/CLARIAH-CZ](https://lindat.mff.cuni.cz/repository/): for linguistic data

If there is no suitable subject-specific repository, general repositories can be used.
- [Zenodo](https://zenodo.org/) maintained by CERN; Community for LangInLife project: [zenodo.org/communities/langinlife](https://zenodo.org/communities/langinlife)
- [Figshare](https://figshare.com/) maintained by Digital Science Company
- [Dataverse](https://dataverse.org/) maintained by Harvard
- [Národní datový repozitář](https://data.narodni-repozitar.cz/) maintained by CESNET

### What metadata to provide for datasets

- Name of the dataset, understandable on its own
- Full names of the creators (authors and contributors) and their permanent identifier (ORCID)
- Date (planned, in case of embargo) of publication
- Publisher and its persistent identifier (ROR)
- Comprehensible description of the dataset
- Information about data availability (time embargo, license, and other details)
- Persistent identifier of the dataset
- Information about funding (funding provider and project number)
- Classification according to scientific disciplines
- Keywords

The list is based on [General recommendations for metadata description of research results (NTK, Czech only)](https://doi.org/10.48813/yt6w-6h15).

<details markdown="1"> 
<summary>Relevant metadata standards</summary>

- [Brain Imaging Data Structure](https://bids.neuroimaging.io/) (BIDS)
- [Component Metadata Specification](https://fairsharing.org/FAIRsharing.2e0599) (CMDI)
- [Investigation Description Format](https://fairsharing.org/FAIRsharing.438d45) (IDF)
- [Linguistic Annotation Format](https://fairsharing.org/FAIRsharing.3cfa81) (LAF)
- [Minimum Information about an fMRI Study](https://fairsharing.org/10.25504/FAIRsharing.s3swh2) (MIfMRI)
- [Open Language Archives Community Metadata](https://fairsharing.org/FAIRsharing.17fbae) (OLAC Metadata)

</details>

## What criteria must published dataset meet to be recognized as a project output

- No non-anonymised sensitive or personal data are included.
- DOI (or another persistent identifier) is assigned.
- Data are deposited in a trusted repository under a clearly stated licence (CC 0, CC BY 4.0 or equivalent).
- Data are deposited in an appropriate format.
- Data are described by rich metadata.
- Metadata are available in a machine readable format.
- Related publication is linked to the dataset by metadata.

## FAIR principles

- **F**indable by both humans and machines thanks to descriptive metadata and persistent identifiers.
- **A**ccessible thanks to trusted repositories.
- **I**nteroperable thanks to open formats and standards.
- **R**eusable  thanks to providing context through metadata and documentation.

[How FAIR are your data checklist](https://zenodo.org/records/3739188)

---

Text is based on the Methodology for Open Science in [the RES-HUM project](https://reshum.muni.cz).

This site was built using [GitHub Pages](https://pages.github.com/).

[Otevřená věda v projektu LangInLife](https://pavla-martinkova.github.io/osprinciples/) © 2025 by [Pavla Martinková](https://github.com/pavla-martinkova) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
