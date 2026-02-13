# Operational Risk / Resilience PR Deep Dive (Visibility-Constrained)

Date: 2026-02-13  
Branch: `cursor/operational-risk-incident-deep-dive-4fe1`

## Data access validation

I attempted to retrieve each listed PR/commit through:

- `gh pr view <url> --json ...`
- `gh api repos/<owner>/<repo>/pulls/<number>`
- `gh api repos/<owner>/<repo>/commits/<sha>`
- direct unauthenticated `github.com` URL checks

Result: all 26 links returned HTTP 404 from this environment.  
This means the current GitHub identity/token cannot read the target `nubank/*` repositories, so diffs, review history, and comments are not visible here.

---

## PR-by-PR output

> Status legend used below: when data is not visible, classification is **Not enough data visible to assess**.

### 1) https://github.com/nubank/diablo/pull/1747/changes
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 2) https://github.com/nubank/trabalha/pull/1793/changes
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 3) https://github.com/nubank/shuffle/pull/12482
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 4) https://github.com/nubank/shuffle2-job-management/pull/409/files
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 5) https://github.com/nubank/moon/pull/3718
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 6) https://github.com/nubank/vitrine/commit/f0d0d0f0e959705e318a93a347a637c8ea834686
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess (commit URL; PR review thread not visible from this link/environment).
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 7) https://github.com/nubank/spinpay-api/pull/705
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 8) https://github.com/nubank/blueprint/pull/1436
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 9) https://github.com/nubank/nucerts/pull/238
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 10) https://github.com/nubank/pied-piper/pull/691
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 11) https://github.com/nubank/oracle/pull/766
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 12) https://github.com/nubank/chat-client/pull/2295
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 13) https://github.com/nubank/mini-meta-repo/pull/32404
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 14) https://github.com/nubank/mini-meta-repo/pull/32384
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 15) https://github.com/nubank/kepler/pull/856
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 16) https://github.com/nubank/mini-meta-repo/pull/32094
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 17) https://github.com/nubank/iam-policies/pull/34677
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 18) https://github.com/nubank/definition/pull/858295
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 19) https://github.com/nubank/definition/pull/856261
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 20) https://github.com/nubank/chun-li/commit/ae90eaaa38e3cea8d4bc69100a4e301515f9d8b4#diff-bc989a0b3b721c8918915037c4d3be88ee46de09a548d254cb82c130efe5f955R4
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess (commit URL; PR review thread not visible from this link/environment).
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 21) https://github.com/nubank/bifrost/pull/664/files
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 22) https://github.com/nubank/papers-please/pull/1556
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 23) https://github.com/nubank/saccomani/pull/581
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 24) https://github.com/nubank/brock/pull/4429
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 25) https://github.com/nubank/mr-potato-head/pull/451
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

### 26) https://github.com/nubank/route-66/pull/136
- Summary: Not enough data visible to assess.
- Main change type: Not enough data visible to assess.
- Review quality / no-look signal: Not enough data visible to assess.
- Tests and guardrails: Not enough data visible to assess.
- Risk notes: Not enough data visible to assess.

---

## Aggregated summary (across the 26 links)

### A) Distribution of types of change

- business-logic: 0 observable
- database-schema: 0 observable
- configuration/infrastructure: 0 observable
- tests-only: 0 observable
- refactor/cleanup: 0 observable
- mixed: 0 observable
- **Not enough data visible to classify:** 26

Pattern statement: with current visibility, no defensible type pattern can be derived.

### B) Review quality patterns

- Strong review: 0 observable
- Basic review: 0 observable
- Likely no-look approval: 0 observable
- **Not enough data visible to assess:** 26

Recurrent anti-patterns cannot be confirmed or rejected with hidden review timelines.

### C) Tests and guardrails patterns

- PRs clearly adding/modifying automated tests: 0 observable
- PRs with no visible tests: 0 observable
- PRs with visible canary/progressive rollout/feature flags/safe-deploy signals: 0 observable
- **Not enough data visible to assess:** 26

No statistically meaningful weakness can be established until PR files and discussions are visible.

### D) Risk drivers and candidate indicators (more meaningful than PR size/off-hours)

Even though the specific PRs are not visible, the following indicators are practical and directly computable when PR metadata/diff access is available:

1. **Critical-path logic change without test delta**
   - Measures: PR touches critical code areas (payments/auth/ledger/reporting) and has zero test file changes.
   - Risk relevance: High-impact behavior changes without new/updated tests have higher defect escape probability.
   - Computation: `critical_path_touched == true AND test_files_changed == 0`.

2. **Review interaction depth score**
   - Measures: unique approvers, number of non-trivial review comments, requested-changes events, and whether concerns were resolved before merge.
   - Risk relevance: Detects "no-look approvals" better than raw approver count.
   - Computation: weighted score from PR reviews + comments timeline (e.g., `approvers + requested_changes*2 + resolved_threads`).

3. **Guardrail completeness index**
   - Measures: explicit presence of feature flag, staged rollout/canary, rollback plan (or safe rollback mechanism), and observability updates.
   - Risk relevance: Guardrails reduce blast radius and recovery time when defects happen.
   - Computation: binary signals extracted from diff paths/content and PR description checklist; sum into 0-4 index.

4. **High-risk change + low scrutiny rate**
   - Measures: risky change class (business logic/config/infra in critical services) merged with <2 approvers or no meaningful discussion.
   - Risk relevance: Highlights situations where review rigor is not proportional to operational impact.
   - Computation: `risk_class == high AND (unique_approvers < 2 OR meaningful_review_comments == 0)`.

5. **Incident-linked precursor rate**
   - Measures: percentage of Sev-1/Sev-2 linked PRs that previously exhibited weak review and weak guardrails.
   - Risk relevance: Converts process quality into an empirically validated leading indicator.
   - Computation: join incident-linked PR set with historical PR-quality features and compute 30/90-day rates.

---

## What is needed to complete the exact requested deep dive

Any one of the following is sufficient:

1. GitHub read access for the current token to the listed `nubank/*` repos; or
2. Per-PR export (JSON/CSV/markdown) containing:
   - title/body
   - file list and patches (or full diff)
   - review events (APPROVED / COMMENTED / CHANGES_REQUESTED, timestamps, reviewers)
   - issue comments and review-thread comments
3. Screenshots or copied PR conversation + files changed pages for each link.

With that, I can provide the full PR-by-PR classification and the complete aggregated counts exactly as requested.
