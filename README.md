# 420 Terp Book v1

For adults 21+ where cannabis is legal.
Follow your local laws. This is general information, not medical advice.
Effects described are what people report, not claims about any condition.
No dosing advice. Vaping and smoking carry health risks; follow your device
maker's instructions. Data is provided "as is" with no warranty.

This package is the compiled public terpene book for 420 Terp Bot. It is a
snapshot of lab numbers from public reports and open datasets. It is not a
live bot, and it does not download or scrape any website.

## What's in this package

- `book/` — the stripped strain book (`index.csv`, `strains/*.md`, flower-only `records.csv`, `glossary.md`, `sources.md`, and the other book files)
- `LICENSE` — CC BY 4.0 applies only to John's own material (glossary text, README, documentation, and the selection and arrangement of the compiled book)
- `NOTICE.md` — data sources and credits, including third-party terms

Third-party data stays under its own terms, listed in `NOTICE.md`. Nothing in
`LICENSE` changes those terms.

## How to use

Unzip this archive and read `book/index.csv` or the strain cards in `book/strains/`.
A separate website zip (`420-terp-book-website.zip`) adds a local `index.html`
that you can open in a browser, with a searchable strain list and HTML cards.

To confirm the zip is intact, check it against `420-terp-book-v1.zip.sha256`:

```
sha256sum -c 420-terp-book-v1.zip.sha256
```

## Credits

See `NOTICE.md` and `book/sources.md`.

Cannlytics, "Cannabis Results" dataset, is licensed CC BY 4.0
(https://creativecommons.org/licenses/by/4.0/; source:
https://huggingface.co/datasets/cannlytics/cannabis_results). Changes were
made: personal, contact, license and ID fields were removed, images were
removed, test and non-flower rows were dropped, units and names were
standardized, and sources were merged. This book is not endorsed by
Cannlytics.

Smith et al. 2022, PLOS ONE, CC0: https://doi.org/10.1371/journal.pone.0267498
Dataset: https://github.com/cjsmith015/phytochemical-diversity-cannabis/

Vergara et al. 2020, Dryad, CC0 (lab testing by Steep Hill Inc.):
https://doi.org/10.5061/dryad.sxksn0314

Connecticut Cannabis Product Registry: https://data.ct.gov/d/egd5-wb6r
(provided "as is"; photos and labels are not included).

Not affiliated with or endorsed by Cannlytics, the study authors, Steep Hill,
Leafly, Weedmaps, any dispensary, or any state agency.

Corrections or name-removal requests: open an issue at https://github.com/jcatkinsoniii/420-terp-book/issues.
