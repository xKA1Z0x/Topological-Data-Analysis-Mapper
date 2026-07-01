
# TDA Mapper Pipeline for Manuscript Release

This repository contains a reproducible pipeline for Topological Data Analysis (TDA) using the Mapper algorithm, as used in our manuscript. The code and notebooks are organized for clarity and ease of use by reviewers, collaborators, and the broader research community.

## Repository Layout
- `requirements.txt` – Python dependencies (install with `pip install -r requirements.txt`).
- `001_Main_Mapper.ipynb` – Loads raw data, filters features, standardizes, and creates the core Mapper structure.
- `002_PostHoc_Mapper.ipynb` – Performs posthoc analysis, color-coding, and saves publication-ready plots.
- `CONTRIBUTING.md` – Guidelines for contributing to this repository.
- `LICENSE` – MIT License for open-source use.

## Data Expectations
- Input data should be in CSV format, with rows as individuals and columns as features, outcomes, or conditions.
- Remove outliers before running the pipeline for best results.

## How to Use
1. Install dependencies: `pip install -r requirements.txt`
2. Run `001_Main_Mapper.ipynb` to process data and generate Mapper structures.
3. Run `002_PostHoc_Mapper.ipynb` for posthoc analysis and figure generation.

## Contributing
See `CONTRIBUTING.md` for guidelines on bug reports, feature requests, and pull requests.

## Author Affiliations
- Author affiliation(s): <Postdoctoral Fellow Research>
- Institution/location: <Shirley Ryan AbilityLab>

## Citation
If you use this codebase, please cite:
- Our manuscript (DOI: <to be added>)
- KeplerMapper: https://doi.org/10.21105/joss.01315
- Any primary datasets as required by their data-sharing agreements.

## Metadata Availability
Some manuscript metadata is not provided in this code repository.

To request missing metadata, please contact the corresponding author:
- Corresponding author: <Arun Jayaraman>
- Email: <a-jayaraman@northwestern.edu>

## License
This project is licensed under the MIT License. See `LICENSE` for details.
