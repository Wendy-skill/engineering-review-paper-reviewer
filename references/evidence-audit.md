# Evidence Audit for Engineering Review Papers

Use this file when figures, tables, coding, references, quantitative summaries, or research gaps are central to the review.

# 1. Claim → Evidence Traceability

For every high-impact claim, identify:

1. the exact claim;
2. the studies or data supporting it;
3. the relevant table, figure, or coding field;
4. whether the source directly reports the claim or the review authors infer it;
5. whether the conclusion is stronger than the evidence.

Treat these as different:

- directly measured;
- directly reported;
- calculated by the review authors;
- inferred from a figure;
- inferred from multiple sources;
- proposed as a methodological recommendation.

Do not silently merge them.

---

# 2. Reference Integrity

Prioritise references that support:

- novelty claims;
- final corpus membership;
- important quantitative values;
- methodological recommendations;
- research gaps;
- reproduced or redrawn figures;
- strong statements such as "no studies", "only one study", "all studies", or "first review".

Check for:

- wrong reference numbers;
- references whose titles/topics do not support the sentence;
- secondary citations used where the primary source should be cited;
- old figure labels after reference-list reordering;
- multiple papers from the same underlying experiment;
- review articles cited as evidence that an original study measured something it may not have measured.

If external verification is unavailable, phrase uncertainty explicitly instead of asserting a mismatch.

---

# 3. Quantitative Coding Audit

When the review contains a heatmap, reporting score, checklist, percentage, or coded matrix:

Require a stable coding rule.

Prefer explicit states such as:

- reported;
- partially reported;
- not reported;
- not applicable;
- not assessable.

Check whether every displayed percentage can be reproduced from the coding table.

If a weighted score is used, require:

- formula;
- weights;
- denominator;
- rationale;
- label that does not misrepresent the score as a raw study percentage.

Example failure:

A chart labelled `Reported (%)` actually uses `1` for full reporting and `0.5` for partial reporting. This is a weighted reporting index, not the percentage of studies that fully reported the item.

---

# 4. Figure Audit

Check:

- axis variable and units;
- whether cumulative distributions are monotonic;
- radius versus diameter;
- scale units such as mm/cm/m;
- legend mapping;
- panel labels;
- reference numbers;
- whether the figure is original, reproduced, adapted, or redrawn;
- whether data extraction from a source is documented;
- whether the caption provides enough information to interpret comparisons.

A visually polished figure can still contain a scientific inconsistency.

Do not correct a suspected unit or variable by guessing. Require source verification when necessary.

---

# 5. Table Audit

Ask two questions:

## A. Is the table internally reliable?

Check:

- definitions;
- units;
- consistent study identifiers;
- missing-data notation;
- derived values;
- source traceability;
- denominator consistency.

## B. Does the table create knowledge?

A synthesis table should ideally reveal at least one of:

- a cross-study pattern;
- a boundary condition;
- a contradiction;
- a methodological trade-off;
- a comparability limitation;
- an evidence gap;
- a decision rule.

If it merely relocates source information into rows and columns, call it descriptive inventory rather than synthesis.

---

# 6. Comparability Audit

For every cross-study numerical comparison, check compatibility of:

- physical quantity;
- numerator and denominator;
- geometry;
- area basis;
- time basis;
- scale;
- operating condition;
- material or particle definition;
- measurement method;
- sampling location;
- normalisation;
- uncertainty;
- data independence.

Do not infer that two values are comparable merely because they share the same unit.

When studies cannot be pooled, record the specific incompatibility rather than writing only "heterogeneity was high".

---

# 7. Framework Evidence Audit

When a framework classifies studies into levels or categories:

Check whether classification occurs at the correct unit.

A whole paper may contain multiple experiments with different evidential levels.

Prefer classification at the level needed by the claim:

- experiment;
- dataset;
- outcome;
- measurement endpoint;
- study comparison.

Do not assign one global level to an entire paper if its components support different kinds of inference.

---

# 8. Research-Gap Audit

For every important gap, classify it as one of:

- **absence gap** — no relevant study found;
- **coverage gap** — a condition/population/scale is underrepresented;
- **reporting gap** — studies may have relevant information but do not report it;
- **measurement gap** — required quantity is not measured;
- **comparability gap** — evidence exists but definitions/conditions prevent synthesis;
- **validation gap** — laboratory/model result lacks the required external comparison;
- **mechanism gap** — a trend exists but the governing explanation is not established;
- **uncertainty gap** — evidence exists but precision/repeatability is insufficient.

Do not convert one gap type into another.

Example:

"No study reports the local concentration needed for normalisation" is not the same as "local concentration has never been measured."

---

# 9. Conclusion Strength Audit

Watch for statements such as:

- only;
- none;
- all;
- first;
- most important;
- more limiting than;
- proves;
- demonstrates;
- universally;
- cannot;
- should always.

For comparative conclusions such as "reporting limits the field more than facility capability", require evidence that actually compares those causes.

For absolute gaps such as "no field validation exists", check whether partial or incomplete validation attempts exist.

A strong conclusion may need to become:

> Existing evidence does not yet demonstrate X under the criteria used in this review.

rather than:

> X has never been studied.

---

# 10. Confidence Calibration

Use:

**High** — directly visible contradiction, reproducible calculation, explicit manuscript statement, or verified source mismatch.

**Medium** — strong methodological concern but requires source detail or author clarification.

**Low** — plausible issue based on incomplete evidence; present as a verification request, not a confirmed error.

Do not inflate confidence to make the review sound decisive.
