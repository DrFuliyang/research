# Repository audit — September 11, 2026

[Research hub](../README.md) · [Selected resources](../REPOSITORIES.md)

The owner authorized account reorganization, repository naming, and cleanup of obsolete or unrelated projects.

## Decisions

| Repository | Decision | Evidence |
| :--- | :--- | :--- |
| research | Retain as the main research hub | Renamed from garch-quant; active research hub published and verified |
| Auto-claude-code-research-in-sleep | Retain local research additions | Default branch has 11 commits not in the upstream default branch; comparison lists seven research skill files |
| scientific-agent-skills | Retain as a supporting resource | Broad skill collection; corrected startup instructions that referenced absent files |
| garch-quant-skill | Retain as a prototype | Python implementation present; README now documents source and validation scope |
| pairs-trading | Retain as a workflow specification | README and SKILL.md present; corrected old account URL |
| translate-book | Retain pending a separate provenance review | GitHub reports no common ancestor with the upstream default branch; uniqueness cannot be inferred |
| riskfolio-risk-parity | Retire non-substantive placeholder | Current `main` contains only `.gitignore`; one branch and no releases or issues were returned in the September 19 review |
| zoro-cli | Retire from research presentation | Small general command-line utility with no documented role in the research programmes |

## Fork cleanup candidates

Default-branch comparisons are against the upstream default branch. A zero ahead count means no unique commits in that comparison, not proof that all branches, tags, issues, or releases are redundant.

| Local repository | Upstream | Ahead | Behind | Branch review |
| :--- | :--- | ---: | ---: | :--- |
| [pdf-craft](https://github.com/DrFuliyang/pdf-craft) | [oomol-lab/pdf-craft](https://github.com/oomol-lab/pdf-craft) | 0 | 83 | Single branch listed |
| [financial-services](https://github.com/DrFuliyang/financial-services) | [anthropics/financial-services](https://github.com/anthropics/financial-services) | 0 | 13 | 32 branches listed; additional branches not compared |
| wechat-article-exporter *(local endpoint absent)* | [wechat-article/wechat-article-exporter](https://github.com/wechat-article/wechat-article-exporter) | 0 | 35 | Historical comparison retained; the local endpoint returned 404 and is absent from the September 19 account inventory |
| [wxdown-service-obsolete](https://github.com/DrFuliyang/wxdown-service-obsolete) | [wechat-article/wxdown-service-obsolete](https://github.com/wechat-article/wxdown-service-obsolete) | 0 | 0 | Single branch listed |
| [wxdown-service](https://github.com/DrFuliyang/wxdown-service) | [wechat-article/wxdown-service](https://github.com/wechat-article/wxdown-service) | 0 | 0 | Single branch listed |
| [docs](https://github.com/DrFuliyang/docs) | [wechat-article/docs](https://github.com/wechat-article/docs) | 0 | 3 | Single branch listed |
| [mprss](https://github.com/DrFuliyang/mprss) | [wechat-article/mprss](https://github.com/wechat-article/mprss) | 0 | 0 | Single branch listed |
| [lumibot](https://github.com/DrFuliyang/lumibot) | [Lumiwealth/lumibot](https://github.com/Lumiwealth/lumibot) | 0 | 582 | At least 100 branches; listing paginated |
| [TradingAgents](https://github.com/DrFuliyang/TradingAgents) | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 0 | 100 | 2 branches listed; additional branches not compared |

All nine historical candidates have been excluded from the selected research resources; eight remain visible in the current account inventory, while `wechat-article-exporter` is absent. Prefer archiving the remaining candidates first if they are no longer needed. Repository deletion should follow a final check for unique branches, tags, releases, and local issues. The upstream of wxdown-service-obsolete is itself archived.

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

- Created the research hub, research guide, replication guide, maintenance record, and live profile README.
- Corrected scientific-agent-skills navigation to match the actual tree.
- Corrected the pairs-trading raw download URL and clarified its specification status.
- Rewrote the garch-quant-skill README around the actual source interface and preserved its existing MIT designation.
- Removed general utility forks from the main research navigation.

## Follow-up review — September 12, 2026

- Verified that the public repository count remains 17 and that `research` and `Drfuliyang` still use `main`.
- Corrected the selected-resource link for `garch-quant-skill`; no cleanup candidate was deleted or archived.
- ARIS's Actions history still exposes two failed runs of a former upstream-sync workflow. The workflow file is absent from current `main`, so no automated repair or synchronization was attempted. Its 11 unique commits and seven listed skill files remain protected.
- No new evidence changes the decision to keep `translate-book` pending a separate provenance review.

## Follow-up review — September 19, 2026

- Confirmed 17 visible repositories. `research` and `Drfuliyang` remain public and use `main`; no newly failed Actions runs were returned after the previous review.
- Removed the dead local link for `wechat-article-exporter`. Its endpoint returns 404 and it is absent from the current inventory; the historical upstream comparison remains for provenance, without attributing how or when the local repository disappeared.
- Rechecked `riskfolio-risk-parity`: `main` contains only `.gitignore`, with one visible branch and no returned releases or issues. It remains a cleanup candidate, but no deletion or archive operation was performed.
- The ARIS preservation requirement remains unchanged: retain the 11 identified unique commits and seven listed research skill files. `translate-book` remains outside redundancy-based cleanup because its upstream comparison previously had no common ancestor.


## Follow-up review — September 26, 2026

- Confirmed the inventory remains 17 visible repositories. Before this review, no default branch in the visible inventory had a commit later than the September 19 hub maintenance update.
- No new failed Actions run was returned. ARIS remains 11 commits ahead and 422 behind its upstream default branch; the seven protected research skill files are present, and current `main` contains only `.github/workflows/lint-skills-helpers.yml`.
- The prior provenance decision for `translate-book` remains unchanged. No cleanup candidate was archived or deleted, and no visibility, collaborator, or license setting was changed.

## Follow-up review — October 3, 2026

- Confirmed 18 visible public repositories. The addition is [prediction_markets_public](https://github.com/DrFuliyang/prediction_markets_public), created September 26 as a fork of [jdkatz21/Prediction_Markets_Public](https://github.com/jdkatz21/Prediction_Markets_Public). Retain both `main` and `garch-extension`; the latter contains local factor code, a calendar, derived factors and a source manifest.
- The [GARCH extension run](https://github.com/DrFuliyang/prediction_markets_public/actions/runs/37033020003) succeeded October 2 (UTC). The inherited [Daily Data Update run](https://github.com/DrFuliyang/prediction_markets_public/actions/runs/37065822748) failed later that day while loading an empty Kalshi private-key value. Its later steps also publish to the upstream authors' S3 bucket. Added an original-repository-only job condition in [commit fb5a2b6](https://github.com/DrFuliyang/prediction_markets_public/commit/fb5a2b61f51299e3c079fba908353e7298c3aa71). No credentials were requested or changed, and neither data workflow was rerun.
- The hub has a separate `data-fetch-20260926` branch. Its four failed diagnostic runs concern three temporary workflow files; those files now contain only a manual no-op message. They are absent from `main`. Historical failures were retained, without rerunning collection or estimation.
- ARIS remains 11 commits ahead of its upstream default branch (434 behind at this review); all seven protected skill files are present. Its two old sync failures remain historical.
- `translate-book` remains protected pending its separate provenance review. No branches, tags, releases, issues or repositories were deleted, and no visibility, collaborator or license setting was changed.

## Administration status

The owner completed repository creation and renaming in GitHub. The connector verified the active research and profile repositories and synchronized their documentation. Archiving and deletion remain outside this connector.

The owner previously deleted GARCHSigma.github.io, sigma.garch.space, bayes.garch.space, copula.garch.space, and macro.garch.space. Their repository endpoints subsequently returned 404.
