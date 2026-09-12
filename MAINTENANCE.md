# Maintenance

[Research hub](README.md) · [Repository directory](REPOSITORIES.md)

## Scope

Maintain this research hub and its links to Fuli Yang's academic homepage, GARCH Institute, IMD, DRP, paper records, and relevant repositories.

## Routine review

1. Read the latest default branch before editing.
2. Check internal links and repository destinations.
3. Verify new paper identifiers, titles, versions, and release availability against author or publisher records.
4. Keep research programmes distinct from workflow tools and upstream forks.
5. Correct documented navigation and wording problems with small, descriptive commits.
6. Record material changes and unresolved access or verification problems.

Do not infer publication status from submission activity or working-paper availability. Keep editorial correspondence and private research materials out of public documentation.

The owner has authorized repository naming and cleanup of obsolete or unrelated projects. Preserve identified local research contributions during cleanup and record the evidence and operation. Changes to visibility, collaborators, licensing, or release of previously private materials require their own explicit instructions. Routine research navigation does not require rerunning empirical analyses.

## Initial review — September 11, 2026

- Initialized the research navigation hub under garch-quant; it has since been renamed research.
- Grouped 17 public repositories into four resource categories and recorded upstream provenance for 11 forks.
- Excluded the five retired website repositories deleted by the owner.
- Matched the five IMD paper links to the IMD website.
- Added replication conventions and a proposed GitHub profile README.
- The browser could read the IMD site. It did not obtain usable main-page text from fuliyang.io, garch.institute, or the DRP site during this review. These owner-specified links are retained; automated retrieval failure is not treated as proof of a broken website.

## Account presentation follow-up

The same-name profile repository is active at [DrFuliyang/Drfuliyang](https://github.com/DrFuliyang/Drfuliyang), and its README has been published.

Suggested account bio:

> Financial econometrics | Institutional Market Dynamics (IMD) | Distributional Regime Persistence (DRP) | GARCH Institute

Use https://fuliyang.io/ as the account website. Pin this research hub first, then prioritize released research packages. Repository metadata and profile pinning require account settings capabilities outside the file-editing tools used for this update.

Current research repository description (verified September 12, 2026):

> Dr Fuli Yang’s research hub — Institutional Market Dynamics (IMD), Distributional Regime Persistence (DRP), financial econometrics, macro-finance, climate risk, and market design.

## Cleanup and naming decisions

See the [repository audit](maintenance/REPOSITORY_AUDIT.md) and [account structure](maintenance/ACCOUNT_STRUCTURE.md). Only the selected research resources are shown in the active directory; the audit records deferred administration operations.

## Review — September 12, 2026

- Confirmed that [research](https://github.com/DrFuliyang/research) and [Drfuliyang](https://github.com/DrFuliyang/Drfuliyang) use `main` as their default branch; the public account inventory remains 17 repositories.
- Corrected a repository-rename regression in `REPOSITORIES.md`: the hub label now reads `research`, and `garch-quant-skill` again points to its existing repository instead of the nonexistent `research-skill`.
- Rechecked the five public IMD paper titles and SSRN identifiers against the IMD programme page. Direct SSRN page retrieval was blocked during this review, so the maintenance process does not claim a fresh SSRN version or file-level verification.
- Checked Actions history for the hub, profile, and selected resources. The only failures returned were two May–June 2026 runs of ARIS's former `sync-skills-from-upstream.yml`; that workflow is absent from the current default branch, which contains `lint-skills-helpers.yml`. No workflow was rerun.
- Automated retrieval produced usable content for the IMD site and the GARCH Institute endpoint, but not for `fuliyang.io` or the DRP endpoint. Those links remain because a crawler failure is not evidence that a site is unavailable.
- No repository was deleted, archived, renamed, or made private. The ARIS unique-commit and seven-skill preservation rule, and the separate provenance treatment for `translate-book`, remain unchanged.
