# The Hydroxyapatite Gum Database

A sourced comparison of what every hydroxyapatite chewing gum brand we track actually publishes: dose per piece, particle form, ingredient disclosure, public lab reports, cited studies, and guarantee terms.

Live, human-readable version: **https://www.minvelle.com/pages/hydroxyapatite-gum-database**

Data: [`data/gum-spec-database.csv`](data/gum-spec-database.csv)

## Why this exists

Fifteen brands sell hydroxyapatite gum online. As of August 2026, only two publish how much hydroxyapatite is in a piece. Several show percentage claims with no source. This dataset records what each brand states publicly, and marks what it does not, so comparisons can happen on facts instead of adjectives.

## Method

- Every value comes from the brand's own website, label imagery, or Amazon listing. Each row carries its source URL.
- **"Not disclosed" is itself the datum.** If a figure is not published anywhere by the brand, it is recorded as not disclosed, never guessed or inferred.
- Facts that could not be verified directly were left out rather than estimated.
- Prices are excluded: pack sizes and channels vary too much for a fair per-piece comparison.
- Kreain, Aurien and Gud Gum+ were added on 28 August 2026, with their cells checked that day. Gud Gum+ is the first brand in the set based outside the United States, so the dataset is no longer scoped to US brands only.
- ApaCare (Cumdente GmbH, Tuebingen, Germany) was added on 29 August 2026, with its cells checked that day. Its product description names tooth enamel minerals (hydroxyapatite) while the ingredient list printed on the same page names calcium carbonate and not hydroxyapatite; both are recorded as facts about what is published, not as claims about the product's contents. It is the first row whose only stated return window is the statutory 14-day right of withdrawal rather than a money-back guarantee.
- Last live re-check: 1 August 2026 (Crait, Enamio, Underbrush, Dentagum, VanMan, Weldental). No brand had started or stopped disclosing; Crait's 70 mg non-nano wording is unchanged word for word. CaviChew's Amazon listing was only partially readable and was not re-verified.

## Read this before comparing milligrams

Nano and non-nano hydroxyapatite are different materials in practice. A milligram of nano-HAp contains vastly more particles and surface area than a milligram of non-nano HAp, and the two interact with enamel differently. Crait's 70 mg non-nano and Minvelle's 5.7 mg nano are both honest disclosures of different things; neither number is "bigger" in any meaningful head-to-head sense. Compare within the same form.

## On the clinical evidence

Exactly one peer-reviewed clinical trial exists on hydroxyapatite gum specifically: Porciani PF, Chazine M, Grandini S., *Journal of Clinical Dentistry* 2014;25(2):32-36 ([PubMed 25122980](https://pubmed.ncbi.nlm.nih.gov/25122980/)), on dentin hypersensitivity. Its gum, dose and protocol differ from every product in this dataset. **It does not validate any current product**, including the maintainer's. No brand listed here has published a clinical trial of its own finished product.

## Conflict of interest, stated plainly

This dataset is maintained by [Minvelle](https://www.minvelle.com), which sells one of the products listed. That is exactly why every cell is sourced and why Minvelle's own row records its gaps (particle size pending, full lab document being added). Check the maintainer's row hardest.

## Corrections

If any figure is wrong, or a brand starts disclosing more, open an issue or email max@minvelle.com. Corrections ship with a note in the commit history, which doubles as a public record of when each brand's disclosure changed.

## License and citation

Data is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely, including commercially, with attribution.

> Minvelle (2026). *The Hydroxyapatite Gum Database.* https://www.minvelle.com/pages/hydroxyapatite-gum-database
