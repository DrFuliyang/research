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
7. If the text reader cannot retrieve SSRN, check the public author or paper page with the browser when available. Record the access method and distinguish browser success from reader failure. Use displayed Posted and Last revised dates separately; do not infer them from Date Written or private account dates.

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

## DRP synchronization — September 15, 2026

- Added the public DRP8 record to the research guide: *Beyond Two Barycenters: Adaptive Complexity in Distributional Regime Geometry*, SSRN 7451619.
- Recorded DRP8 within the measurement and estimator-contribution boundary: prototype complexity, identity stability, and the sufficiency of a two-anchor representation. No journal-submission status, private materials, or unverified empirical claims were published.
- Synchronized the GitHub navigation with the owner-confirmed DRP programme-page update. Automated retrieval still did not return usable DRP page content, so no page-build or deployment claim was inferred from the crawler result.

## Review — September 19, 2026

- Confirmed 17 visible repositories. [research](https://github.com/DrFuliyang/research) and [Drfuliyang](https://github.com/DrFuliyang/Drfuliyang) remain public and use `main`; the latest hub change is the public DRP8 homepage entry.
- Checked all seven Markdown files in the hub: no missing relative-link targets were found. The profile, programme navigation, DRP8 SSRN 7451619 entry, selected-resource links, and repository labels remain internally consistent.
- Rechecked the five IMD paper identifiers against the public IMD programme page. No new version claim was added. The GARCH Institute endpoint responded, while automated retrieval still produced no usable content for `fuliyang.io` or the DRP page; those crawler results were not treated as evidence of failure.
- Checked Actions history across all 17 visible repositories. No failed run dated after September 12 was returned. ARIS's two historical failures belong to the removed upstream-sync workflow and remain documented without rerunning it.
- Updated the repository audit because `wechat-article-exporter` now returns 404 and is absent from the account inventory. Also clarified that `riskfolio-risk-parity` is non-substantive rather than literally empty: its current tree contains only `.gitignore`.
- Reviewed `maintenance/ACCOUNT_STRUCTURE.md`; no structural change was required. No repository was deleted, archived, renamed, made private, or otherwise administratively changed.

## Review — September 26, 2026

- Confirmed 17 visible repositories. [research](https://github.com/DrFuliyang/research) and [Drfuliyang](https://github.com/DrFuliyang/Drfuliyang) remain public on `main`; before this review, no visible default branch had a commit later than the September 19 maintenance update.
- Rechecked all seven Markdown files in the hub and the profile navigation; no missing relative-link target was found. Added the newly public *Oil-Price Innovations and the Treasury Term Premium: Evidence from 2010–2026* (SSRN 7497760, posted September 23) to the Japan macro-finance guide.
- Checked current SSRN PDF title pages for DRP5 and DRP6: DRP5 is *Geometric Stress Coordinates for Conditional Tail Forecasting: Soft Distributional Routing across Equity Markets* (SSRN 7375598), and DRP6 is *Conditional Portability of Geometric Stress Coordinates: A Frozen Eight-Market Test of Geometric Tail Routing* (SSRN 7377778). DRP8 remains the latest DRP entry surfaced in the hub.
- A September 25 revision copy of SSRN 7324139 uses the title *Futures Before Fungibility: Benchmark Governance and Regulatory Friction in GPU Compute Markets*, while the public search result still exposes the earlier title. The GitHub guide was not changed until the public record and revision metadata converge.
- The GARCH Institute endpoint returned a page, but the automated reader again obtained no usable body text from `fuliyang.io`, the IMD endpoint, or the DRP endpoint. Existing owner-specified links were retained; retrieval limitations were not treated as website failure.
- Actions history across all 17 repositories contains no new failed run. ARIS still has only the two historical failures of the removed sync workflow; its comparison remains 11 commits ahead of upstream, and all seven protected research skill files remain present.
- Reviewed `maintenance/REPOSITORY_AUDIT.md` and `maintenance/ACCOUNT_STRUCTURE.md`. No repository was deleted, archived, renamed, made private, or changed administratively.

## Navigation correction — September 26, 2026

- Added two omitted public records after checking SSRN: *Japan's Fiscal Duration: A Measurement Architecture for Contractual Refinancing Exposure and the BOJ Balance Sheet* (7494820), and *From Gatekeeping to Accountability: Institutional Tension in Hong Kong's 2026 Spin-off Reform* (7509761).
- Moved the oil-price / Treasury term-premium paper (7497760) out of the Japan section into Energy and US macro-finance. The earlier placement was a classification error.
- Added DRP5's current author-verified title and direct SSRN 7375598 link to the DRP guide, retaining its conditional forecasting and calibration boundaries. This is a GitHub documentation update, not a claim that the programme website or SSRN metadata was edited.
- Follow-up retrieval returned IMD page text and DRP page text at https://drp.fuliyang.io/; the academic homepage was visible in search results, but direct extraction still returned no body text. Index availability is distinct from live-page verification. The indexed DRP5 programme title still differed from the author-verified title.

## Review — October 3, 2026

- Confirmed 18 visible public repositories through the authorized connection. The hub and profile still use `main`; the hub started this review at `ad359d264cbbe0596717b49391c65d606d0754cf`.
- Added the new prediction-market fork and its separate `garch-extension` branch to the resource directory and account structure, preserving attribution to Diercks, Katz and Wright and distinguishing the data transformation from paper-result validation.
- Added the missing Energy and US macro-finance entry to the hub's empirical-research table. The oil/Treasury paper was already correctly filed in the research guide.
- Checked all seven hub Markdown files for relative file and heading targets and checked the profile's repository destinations. No missing internal target was found.
- Reviewed Actions histories across all 18 repositories. The prediction-market extension succeeded October 2 (UTC); the inherited raw collector failed on missing Kalshi credentials. Restricted its collection and upstream S3 publishing job to the original repository in [fb5a2b6](https://github.com/DrFuliyang/prediction_markets_public/commit/fb5a2b61f51299e3c079fba908353e7298c3aa71). Verification was a source readback and condition check, not a fresh Actions run. The temporary hub diagnostics are now manual no-ops; ARIS's two old sync failures remain historical.
- Rechecked the five IMD titles and SSRN identifiers against the [programme page](https://imd.garch.institute/). Direct SSRN retrieval returned HTTP 403 for DRP5, DRP8 and 7324139. Search indexes disagree on the compute-paper title, so no new paper-version or PDF verification is claimed.
- Corrected the maintenance state for DRP5: after the September 26 GitHub update, the programme website was also published with the updated title, conditional-results summary and SSRN 7375598 link. The hosting service currently confirms the [DRP site](https://drp.fuliyang.io/) is active at version 5, last updated September 26; IMD remains active at version 11. This hosting evidence is distinct from crawler extraction, which still did not return a usable DRP body. The academic and institute homepages likewise returned no extracted body text; no site was classified as dead.
- Preserved ARIS's 11 identified unique commits and seven skill files, and retained the separate provenance treatment of `translate-book`. No raw empirical estimation, trading, repository deletion, visibility change, collaborator change or license change was performed.

Next review: verify that the inherited collector skips in this fork, check the independent extension's next scheduled result, and revisit SSRN revision metadata when direct public retrieval becomes available.


## Review — October 19, 2026

- Confirmed 18 accessible public repositories through the authorized GitHub connection. The hub and profile remain on `main`; their starting heads were `b2788dcce5fc0be3e0056694ec4627c33a67b8ff` and `a9443925aee4fd97286013fe78336cd2e386f893`. Reviewed account structure; no inventory change required a restructuring.
- Checked all seven hub Markdown files: all 28 pre-edit relative file/heading links resolved. Profile repository destinations remain present. Updated the IMD source-review date after matching the five programme titles and identifiers.
- The [DRP institute endpoint](https://drp.garch.institute/) returned usable programme text in this review. DRP5's updated title and DRP8 are present in both the site and hub. Added the missing DRP6 direct navigation entry using the programme title, subtitle and SSRN 7377778 destination. The alternate `drp.fuliyang.io` endpoint did not return usable text through the reader; no broken-site conclusion was drawn.
- Added four public bibliographic records omitted from the selective guide: SSRN 7598018 (ESG extraction), 7590558 (AI drug discovery), 7574438 (AI capital expenditure; retaining all three authors), and 7531538 (index-inclusion funding pressure). Titles, authors and posted dates came from publicly indexed SSRN records. No private materials, submission status or inferred results were published.
- Direct SSRN requests for DRP5, DRP6 and DRP8 remained blocked or inaccessible. The index still surfaces an older DRP5 title, whereas the programme page matches the author-confirmed updated title. Retained the updated title and made no latest-PDF verification claim. The academic and institute homepages returned titles but no extracted body; crawler limitations remain distinct from site availability.
- Inspected Actions histories across all 18 repositories: no failed run after October 3 was returned. The independent prediction-market extension succeeded on October 9 and 16 (UTC); the inherited collector was skipped on both dates. The [October 16 skipped run](https://github.com/DrFuliyang/prediction_markets_public/actions/runs/38958172426) confirms the October 3 guard now works in scheduled execution. Updated the resource directory's stale October 2 success date. Read the extension's source manifest; its presence is not a fresh recomputation or hash-verification claim.
- ARIS remains 11 commits ahead of upstream and is now 441 behind; all seven protected research skill paths remain present. Historical sync failures and hub diagnostic failures were not rerun. Retained `translate-book` pending its separate provenance review.
- No workflow was triggered, empirical estimation rerun, or repository deleted, renamed, archived or administratively changed. Website content was inspected, not redeployed.

Next review: follow the existing extension schedule, revisit direct SSRN version verification, and check public paper navigation for new records. Public search coverage is not a complete author-catalogue audit.


## Public catalogue reconciliation — October 19, 2026

- Reconciled 34 legible title–abstract-ID pairs from two owner-provided screenshots of publicly available SSRN papers. Added [research/PAPERS.md](research/PAPERS.md) and linked it from the hub and guide. This is a partial catalogue, not 34 newly published papers or an exhaustive account inventory.
- The additions include SSRN 7621100, 7620802, 7608119, 7600100, 7531599, 7531578, 7527141 and 7520379, alongside earlier papers missing from individual theme navigation. Used only public bibliographic titles and identifiers; no administrative status, account metrics, private manuscript, or screenshot was published.
- The final partially cut-off row was not transcribed. The screenshots' account dates were not relabelled as posting or PDF-revision dates. Search queries for the newly visible identifiers returned no matches, so the source of these mappings remains the owner-provided public-catalogue evidence, not independent live SSRN or PDF verification.
- Retained the previously verified coauthor information in the research guide; the catalogue does not infer a sole-author list from the account's submission-owner column. All existing programme mappings and repository history remain intact.


## Live SSRN catalogue reconciliation — October 19, 2026

- Browser access succeeded without sign-in for the public author page and the DRP5 and DRP2 detail pages. The earlier HTTP 403 results are limitations of that text-retrieval method, not evidence that SSRN is inaccessible. This live check supersedes the current access blockers and screenshot-only provenance described earlier today, while retaining those historical observations.
- Replaced the 34-entry partial catalogue with all 108 public author-page records: 108 unique SSRN identifiers, 17 coauthored records, and 22 rows displaying a Last revised date. Preserved author order and exact normalized public titles; omitted account statistics and private information. Added `research/papers.json` for future comparisons.
- Verified the copied record payload against the browser-extracted payload with a transfer checksum. This verifies transcription consistency, not PDF authenticity or data/result replication. Updated the hub and guide catalogue links/counts, and checked the IMD dynamic-correlation entry against its full public title.
- DRP5's updated title and September 25 revision are confirmed on its detail page; DRP6's full title and September 25 revision are confirmed in the author list. DRP2's detail page confirms an October 18 revision and its new past-only KS comparison. Added direct DRP2 and Global Stress navigation, preserving their respective two- and three-author lists.
- The author list shows October 18 revisions for DRP2 (7245378), Global Stress (7259360) and compute derivatives (7324139). The compute paper's current public title is *Futures Before Fungibility: Benchmark Design and Market Formation in Compute Derivatives*; this resolves the title uncertainty carried in earlier reviews. Revised dates are public metadata; no PDF inspection, journal status or empirical validation is inferred.
- The catalogue is a snapshot of the 108 displayed records at this check, not a claim of permanent completeness. Existing research programmes, fork attribution, protected ARIS additions, repository visibility and licenses remain unchanged.


## Journal publication follow-up — October 19, 2026

- Added *Where public climate signals remain visible: issuer compression and debt-rating sorting in China*, Fuli Yang, *Journal of Financial Reporting and Accounting*, DOI 10.1108/JFRA-08-2026-0832, to a distinct journal-publication section in the hub, guide and catalogue.
- The live personal publication page labels it Published / ahead-of-print. Crossref's DOI API independently confirms type `journal-article`, the title, Fuli Yang as author, journal, online publication date October 7, 2026 and pages 1–20; volume and issue are absent. The publisher page presented a Cloudflare security check, so no publisher-body inspection is claimed. No private acceptance or submission correspondence was used.
- Stored this journal record separately from the 108 SSRN records in the structured catalogue. No unverified equivalence with an earlier differently titled SSRN paper, or total of distinct works, is inferred. The profile README is being synchronized with the catalogue and journal-publication navigation.
- Browser access also returned usable body content for `fuliyang.io` and its publications page. This supersedes the earlier text-reader-only homepage extraction limitation; no website edits were made.
