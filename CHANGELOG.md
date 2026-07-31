# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-07-31

### Added
- Initial repository for the Climate Policy Uncertainty (CPU) index for Portugal.
- `config/config.json` documenting the exact boolean search query, languages,
  regions, and reporting interval used to build the index.
- `config/sources.csv` listing the media sources with coverage windows and
  importance weights.
- `data/raw/num_hits.csv` with the raw monthly article counts (matching articles
  and total articles) per source.
- `data/processed/index.csv` and `data/processed/index.xlsx` with the computed
  index (four series), covering 1998-01 through 2026-06.
- `README.md` with the methodology, a reproducible `config/` → `data/raw/` →
  `data/processed/` pipeline, and a per-file data dictionary.
- `CITATION.cff` with machine-readable citation metadata for the companion paper,
  published in *The Journal of Economic Asymmetries*, Volume 32, 2025, e00426
  (https://doi.org/10.1016/j.jeca.2025.e00426).
- `LICENSE` — Creative Commons Attribution 4.0 International (CC BY 4.0).
- `.gitattributes` for cross-platform LF normalization.
