# New Zealand: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in New Zealand: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

The text read is the consolidated version of the Residential Tenancies Act 1986 on legislation.govt.nz "as at 1 December 2025". Later amendments and the Residential Tenancies Regulations were not checked. Boarding houses, fixed-term rules and the Tenancy Tribunal process are only touched where a row says so.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Residential Tenancies Act 1986. | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| contract_form | Written agreement | The landlord must ensure the tenancy agreement is in writing, sign it and give the tenant a copy before the tenancy starts; the tenant must sign it. Failing to do so is an unlawful act and an infringement offence (s 13). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| deposit | Bond cap | A landlord may require a general bond of no more than 4 weeks' rent; if rent is lawfully increased a further bond up to the increase in 4 weeks' rent may be required. Requiring more is an unlawful act and an infringement offence (s 18). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| deposit | Key money | Requiring key money for granting, continuing, extending, varying or renewing a tenancy, or for an assignment or sub-letting, is prohibited without the Tribunal's consent (s 17). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| rent_payment | Rent in advance | A landlord must not require rent more than 2 weeks in advance, or before the period already paid has expired (s 23). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| rent_increase | Rent increase rules | Rent may be increased only by written notice stating the new amount and the date it becomes payable, at least 60 days after the notice (28 days for boarding houses); not within 12 months of the tenancy start or the last increase; during a fixed term only if the agreement permits (s 24). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| termination | Landlord notice (periodic tenancy) | A landlord may end a periodic tenancy in any case by at least 90 days' notice, or at least 42 days' notice if, for example, the owner needs the home as their principal residence for at least 90 days or the owner must give vacant possession to a buyer (s 51(1), (2)). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |
| contract_form | Short fixed terms | Sections 25 to 28 and 51 do not apply to a tenancy for a fixed term of 90 days or less if the parties agree in writing before the start that it will not be extended beyond 90 days in total (s 7). | [New Zealand Legislation (Parliamentary Counsel Office)](https://www.legislation.govt.nz/act/public/1986/0120/latest/whole.html) |

## Files

| File | Content |
| --- | --- |
| `new-zealand_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *New Zealand: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-new-zealand-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
