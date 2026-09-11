# Replication guide

[Research hub](README.md)

This is the release convention for future paper-specific research packages.

## Minimum release contents

| File or directory | Required information |
| :--- | :--- |
| README.md | Research question, paper/version link, supported outputs, and exact run commands |
| Environment file | Required language and dependency versions |
| data/README.md | Sources, acquisition dates, sample coverage, units, transformations, and access restrictions |
| src/ or scripts/ | Executable analysis code with configuration separated from computation |
| results/README.md | Mapping from commands and outputs to paper tables and figures |
| CHANGELOG.md | Material changes to data, specifications, code, and results |
| CITATION.cff | Verified author, title, date, version, and paper identifier where available |
| License information | Explicit terms for code and any separately distributed data |

## Reproducibility record

Record the data snapshot, input hashes where appropriate, random seeds, sample rules, parameter choices, and the commit used for a reported result. Document restricted inputs with acquisition instructions and a clearly labelled public example where feasible.

Keep paper versions and code versions distinct. Describe exactly which outputs were reproduced, the command used, and the environment in which the check ran.

For DRP, specify coordinates, normalization, calibration windows, and evaluation samples. For crypto roughness, specify sampling frequency, estimators, horizons, and shared sample definitions. For macro-finance and market-design studies, document event times, institutional rules, and source vintages.

## Availability language

- **Released and checked:** identify the exact outputs reproduced from the released inputs.
- **Code released; restricted inputs required:** explain how to obtain the missing inputs.
- **Illustrative example:** identify the demonstration's scope.
- **In preparation:** use this only for work that has actually begun.

Update availability from release evidence. A research topic or working paper entry alone does not establish a public replication package.
