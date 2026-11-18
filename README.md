# Border Tech Validation

A static page for validating the 1,219 model-coded border-technology rows from the 3-5 November 2026 pipeline run, following the project's Validation Protocol (Stage 1: source and link verification; Stage 2: content cross-referencing).

**Open it:** https://joshuawangia.github.io/border-tech-validation/

## How to validate

1. Pick a row. Filter by country or by rows that still need a decision.
2. Stage 1: open each source link and tick *Link opens*, *Publisher matches* and *Meets standard*. Confirm or change the proposed tier.
3. Stage 2: compare each coded value with the source. Click *Wrong* only for an unambiguous fix, and give the correct value and what the source says. Flag judgment calls for the PI.
4. Choose a status (Verified, Corrected, Flagged - Source Issue, Flagged - Content Mismatch, Unable to Verify), write notes, and save.

Decisions are stored in your browser only. **Click Download CSV at the end of each session and send the file to Joshua.** To continue on another computer, use Load CSV there.

## Contents

- `index.html` - the page
- `rows.json` - the rows, their sources, proposed source tiers, pipeline notes and open review flags

None of these rows are validated. They were coded by a model (`gpt-6-astra`) from English-language web sources and every row is flagged for human review.
