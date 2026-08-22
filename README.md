# Metafore — Experiment Dataset

Repository for organizing and versioning the data and annotation materials of the metaphor experiment.

## Repository structure

- `data/raw/` — original, unmodified source datasets.
- `data/intermediate/` — intermediate processing stages.
- `data/annotated/` — annotated and normalized datasets.
- `docs/` — annotation guidelines and project documentation.
- `metadata/` — metadata describing datasets and experimental materials.
- `scripts/` — scripts used for processing or validation.
- `CHANGELOG.md` — record of substantive dataset and annotation changes.

## Data policy

Files in `data/raw/` should be preserved as received and should not be silently overwritten during annotation or cleaning. Derived versions belong in the appropriate downstream directory and should be committed with a descriptive message.

## Initial dataset

The first dataset added to this repository is `data/raw/meta_v3.csv`, containing the corpus metaphors and the completion prompts used in the participant questionnaires.
