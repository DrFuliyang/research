# Research resources

[Research hub](README.md) · [Research guide](research/README.md)

The main research identity is organized around IMD, DRP, and the empirical fields in the research guide. Supporting resources are listed below according to their actual contents.

## Selected resources

| Repository | Role | Current scope |
| :--- | :--- | :--- |
| [research](https://github.com/DrFuliyang/research) | Research hub | Programme navigation, papers, and release conventions |
| [Auto-claude-code-research-in-sleep](https://github.com/DrFuliyang/Auto-claude-code-research-in-sleep) | Research workflows | Fork with local additions for GARCH, macro-finance, ESG, and related research |
| [scientific-agent-skills](https://github.com/DrFuliyang/scientific-agent-skills) | Supporting skill collection | Scientific references and skills; selected research navigation added |
| [garch-quant-skill](https://github.com/DrFuliyang/garch-quant-skill) | Modelling prototype | EGARCH/LSTM source; empirical validation remains a separate task |
| [pairs-trading](https://github.com/DrFuliyang/pairs-trading) | Workflow specification | README and skill specification; standalone backtest implementation not included |

## Prediction-market data resource

[Prediction Markets Public](https://github.com/DrFuliyang/prediction_markets_public) is a fork of [jdkatz21/Prediction_Markets_Public](https://github.com/jdkatz21/Prediction_Markets_Public), the replication package for Diercks, Katz and Wright's *Kalshi and the Rise of Macro Markets*. Preserve the upstream authorship, citation and data-use terms.

The separate [GARCH extension](https://github.com/DrFuliyang/prediction_markets_public/tree/garch-extension/garch_extension) adds a meeting-frequency factor layer from public upstream distributions and moments. Its [source manifest](https://github.com/DrFuliyang/prediction_markets_public/blob/garch-extension/garch_extension/data/source_manifest.json) records input and output hashes. This is a data transformation resource; workflow success does not validate a paper's empirical results.

The extension workflow last completed successfully on October 2, 2026 (UTC). The inherited raw collector and upstream S3 publisher are restricted to the original repository; they are not required by the extension.

## Paper-specific packages

Paper-specific repositories will be added as documented releases become available. Their README files should identify the paper version, inputs, run commands, and reproduced outputs.

## Legacy inventory

Other utility repositories have been removed from the main navigation. Their existence, upstream provenance, and cleanup decisions are recorded in the [repository audit](maintenance/REPOSITORY_AUDIT.md). Removal from this navigation does not mean a repository has been deleted.

See the [account structure](maintenance/ACCOUNT_STRUCTURE.md) for the naming and presentation plan.
