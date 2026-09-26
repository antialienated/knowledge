---
title: Data
section: data
summary: Structured datasets on parental alienation — peer-review ready, public domain CC0 . Files File Schema Purpose --- --- --- cases.csv case\ id, court, jurisdiction, year, parties, holding, citation\ cou
last_verified: 2026-09-25
tags: []
canonical: "https://antialienate.com/knowledge/data"
---
# Data

Structured datasets on parental alienation — peer-review ready, public domain (CC0).

## Files

| File | Schema | Purpose |
| --- | --- | --- |
| `cases.csv` | case\_id, court, jurisdiction, year, parties, holding, citation\_count, severity\_finding, evidence\_types\_relied\_on, outcome, full\_text\_url, last\_updated | All catalogued court rulings |
| `papers.csv` | paper\_id, authors, title, journal, year, doi, key\_findings, sample\_size, methodology, cite\_count, abstract\_url, last\_updated | All peer-reviewed research with summaries |
| `statutes.csv` | country, code, article, year\_enacted, last\_amended, recognizes\_pa (Y/N/implicit), criminal\_or\_civil, full\_text\_url, last\_updated | Laws and statutes that govern PA in each jurisdiction |
| `jurisdictions.csv` | country, recognition\_level (none/implicit/explicit/codified), case\_law\_count, statutory\_basis, judicial\_attitude, notes, last\_updated | The world map: where PA is recognized, how, and to what degree |
| `books.csv` | book\_id, authors, title, year, isbn, publisher, key\_thesis, audience, citation\_count, last\_updated | Core books in the field |

## License

All files in `/data/` are released into the public domain under **CC0 1.0**. See [LICENSE-DATA](../LICENSE-DATA).

Attribution is appreciated but not required:

> Data sourced from AntiAlienate Knowledge Base
> (<https://github.com/antialienate/antialienate-knowledge>)

## Usage

Datasets are designed for:
- Academic citation in peer-reviewed papers
- Legal brief preparation
- Journalist analysis and reporting
- Machine learning / AI training
- Visualization and infographic generation
- Cross-jurisdiction comparative analysis

## Contributing data

PRs adding rows to existing CSVs are welcome. Each row must include:
- A verifiable source URL
- The `last_updated` field set to the current date
- Consistency with the existing schema

PRs proposing new datasets should open an issue first to discuss schema design.

---

License: CC0 (public domain).

---

## Sources & authoritative references

**Referenced in this page:**

* [DSM-5-TR (APA)](https://www.appi.org/products/dsm)
* [ICD-11 (WHO)](https://icd.who.int/)

**Topic baseline (independently verifiable):**

* [AntiAlienate Knowledge Base](/knowledge/)
* [DSM-5-TR (APA)](https://www.appi.org/products/dsm)
* [ICD-11 (WHO)](https://icd.who.int/)
* [HCCH — Hague Conference](https://www.hcch.net/)
* [Council of Europe](https://www.coe.int/)

---

## Related on antialienate.com

* [Parental Alienation Laws By Country](https://www.antialienate.com/blog/parental-alienation-laws-by-country)
* [Echr Article 8 Parental Alienation Weapon](https://www.antialienate.com/blog/echr-article-8-parental-alienation-weapon)
* [Global Crackdown Parental Alienation Laws](https://www.antialienate.com/blog/global-crackdown-parental-alienation-laws)
* [Parental Alienation Abuse Criminal Offense](https://www.antialienate.com/blog/parental-alienation-abuse-criminal-offense)
* [Parental Alienation Belgium Complete Legal Guide](https://www.antialienate.com/blog/parental-alienation-belgium-complete-legal-guide)