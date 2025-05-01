# Dependency Update Adoption Patterns in the Maven Software Ecosystem

## Overview
This research investigates how software developers adopt new versions of dependencies in the Maven ecosystem. We analyze two key metrics:
- **Adoption lifespan**: The time between first and last adoption of a specific version
- **Adoption reach**: The number of dependent packages adopting a specific version

Our analysis examines how these adoption patterns correlate with:
1. Semantic change size (major, minor, patch versions)
2. Maintenance activity of upstream packages

## Key Findings
- Adoption latency in the Maven ecosystem follows a log-normal distribution
- Adoption reach exhibits an exponential decay distribution
- Major version changes (breaking changes) have longer adoption lifespans
- Highly maintained packages have shorter adoption lifespans
- Packages with larger semantic changes have more dependents
- Packages with low and medium maintenance rates have more dependents

## Data and Methodology
We leveraged the Goblin Weaver framework to analyze the Maven Central Dependency Graph containing approximately:
- 7.5 million package versions across 380,000 unique artifacts
- Over 30 million dependency relationships

## Authors
- Baltasar Berretta - The College of Wooster
- Augustus Thomas - The College of Wooster
- Heather Guarnera - The College of Wooster

## Replication
A full replication package is available in our [Zenodo repository](https://zenodo.org/records/14291958).

## Citation
If you use this research in your work, please cite:
```
@inproceedings{berretta2025dependency,
  title={Dependency Update Adoption Patterns in the Maven Software Ecosystem},
  author={Berretta, Baltasar and Thomas, Augustus and Guarnera, Heather},
  booktitle={Proceedings of IEEE Conference},
  year={2025},
  organization={IEEE}
}
```
