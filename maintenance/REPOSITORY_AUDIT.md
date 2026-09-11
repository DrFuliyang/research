# Repository audit — September 11, 2026

[Research hub](../README.md) · [Selected resources](../REPOSITORIES.md)

The owner authorized account reorganization, repository naming, and cleanup of obsolete or unrelated projects.

## Decisions

| Repository | Decision | Evidence |
| :--- | :--- | :--- |
| garch-quant | Retain; rename to research when repository administration is available | Active research hub published in this maintenance pass |
| Auto-claude-code-research-in-sleep | Retain local research additions | Default branch has 11 commits not in the upstream default branch; comparison lists seven research skill files |
| scientific-agent-skills | Retain as a supporting resource | Broad skill collection; corrected startup instructions that referenced absent files |
| garch-quant-skill | Retain as a prototype | Python implementation present; README now documents source and validation scope |
| pairs-trading | Retain as a workflow specification | README and SKILL.md present; corrected old account URL |
| translate-book | Retain pending a separate provenance review | GitHub reports no common ancestor with the upstream default branch; uniqueness cannot be inferred |
| riskfolio-risk-parity | Retire empty placeholder | Empty at initial inventory |
| zoro-cli | Retire from research presentation | Small general command-line utility with no documented role in the research programmes |

## Fork cleanup candidates

Default-branch comparisons are against the upstream default branch. A zero ahead count means no unique commits in that comparison, not proof that all branches, tags, issues, or releases are redundant.

| Local repository | Upstream | Ahead | Behind | Branch review |
| :--- | :--- | ---: | ---: | :--- |
| [pdf-craft](https://github.com/DrFuliyang/pdf-craft) | [oomol-lab/pdf-craft](https://github.com/oomol-lab/pdf-craft) | 0 | 83 | Single branch listed |
| [financial-services](https://github.com/DrFuliyang/financial-services) | [anthropics/financial-services](https://github.com/anthropics/financial-services) | 0 | 13 | 32 branches listed; additional branches not compared |
| [wechat-article-exporter](https://github.com/DrFuliyang/wechat-article-exporter) | [wechat-article/wechat-article-exporter](https://github.com/wechat-article/wechat-article-exporter) | 0 | 35 | 4 branches listed; additional branches not compared |
| [wxdown-service-obsolete](https://github.com/DrFuliyang/wxdown-service-obsolete) | [wechat-article/wxdown-service-obsolete](https://github.com/wechat-article/wxdown-service-obsolete) | 0 | 0 | Single branch listed |
| [wxdown-service](https://github.com/DrFuliyang/wxdown-service) | [wechat-article/wxdown-service](https://github.com/wechat-article/wxdown-service) | 0 | 0 | Single branch listed |
| [docs](https://github.com/DrFuliyang/docs) | [wechat-article/docs](https://github.com/wechat-article/docs) | 0 | 3 | Single branch listed |
| [mprss](https://github.com/DrFuliyang/mprss) | [wechat-article/mprss](https://github.com/wechat-article/mprss) | 0 | 0 | Single branch listed |
| [lumibot](https://github.com/DrFuliyang/lumibot) | [Lumiwealth/lumibot](https://github.com/Lumiwealth/lumibot) | 0 | 582 | At least 100 branches; listing paginated |
| [TradingAgents](https://github.com/DrFuliyang/TradingAgents) | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 0 | 100 | 2 branches listed; additional branches not compared |

All nine have been excluded from the selected research resources. Prefer archiving these candidates first if they are no longer needed. Repository deletion should follow a final check for unique branches, tags, releases, and local issues. The upstream of wxdown-service-obsolete is itself archived.

## Preserved research additions

The ARIS fork comparison identifies:

- skills/deep-research-protocol/SKILL.md
- skills/esg-research/SKILL.md
- skills/finance-lit/SKILL.md
- skills/garch-survey/SKILL.md
- skills/korean-trade-research/SKILL.md
- skills/macro-research/SKILL.md
- skills/quant-research-pipeline/SKILL.md

These paths are preserved in their existing repository. No migration or skill-content rewrite was performed.

## Completed changes

- Created the research hub, research guide, replication guide, maintenance record, and profile draft.
- Corrected scientific-agent-skills navigation to match the actual tree.
- Corrected the pairs-trading raw download URL and clarified its specification status.
- Rewrote the garch-quant-skill README around the actual source interface and preserved its existing MIT designation.
- Removed general utility forks from the main research navigation.

## Administration status

Repository creation, renaming, archiving, and deletion are not exposed by the connector used for this work. This pass did not perform any of those operations.

The owner previously deleted GARCHSigma.github.io, sigma.garch.space, bayes.garch.space, copula.garch.space, and macro.garch.space. Their repository endpoints subsequently returned 404.
