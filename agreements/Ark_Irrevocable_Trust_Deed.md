# Ark Irrevocable Trust Deed — DRAFT v0.1

**Status:** Public draft for comment  
**Intended execution:** After public review and counsel approval  
**Maintained by:** Ark Foundation (acting trustee)  
**Repository of record:** https://github.com/ArkTrust/ark-irrevocable-trust

---

## Plain-Language Summary (non-binding)

- **Mission:** Build a multi-century engine that invests in broad ownership of productive businesses and, once large enough, provides an equal monthly stipend to every person on Earth.
- **Investments:** Own businesses via broad, low-cost index funds/ETFs. **Do not** invest in commodities, land, or precious metals.
- **Trigger:** Distributions begin when Fund **NAV ≥ $15,000 × world population (in 2024 USD, inflation-adjusted)**.
- **Stipend target:** At trigger (and thereafter), target **~0.3% of NAV per month** (≈3.6%/yr), and **not less than $50/month/person** in real (inflation-adjusted) USD when feasible under the trigger constraint.
- **Values:** Longevity, neutrality, transparency, and equal distribution (not means-tested).
- **Governance:** Foundation acts as fiduciary trustee within strict deed constraints; successor trustee process is defined.
- **Transparency:** Publish non-PII metrics and policies openly; changes occur by pull request with public rationale.
- **Irrevocability:** Becomes **irrevocable 10 years** after the Effective Date (see Article 10).

> This summary is a reader’s guide only; the Articles control.

---

## Article 1 — Definitions

1. **Trust / Fund / NAV**  
   - **Trust**: The Ark Irrevocable Trust created by this deed.  
   - **Fund**: All property of the Trust in aggregate.  
   - **NAV**: Good-faith estimate of the Fund’s net asset value in USD (market close), net of liabilities.

2. **Real USD (Inflation-Adjusted)**  
   - Dollar amounts “in 2024 USD” are adjusted using **U.S. CPI-U** (or a substantially similar widely accepted index if CPI-U is unavailable), using 2024 annual average as the base.

3. **World Population**  
   - Most recent **United Nations DESA** estimate or, if unavailable, a substantially similar widely accepted source, with the source cited in public metrics.

4. **Trigger Level**  
   - The condition **NAV ≥ ($15,000 × world population)**, expressed in **2024 USD**.

5. **Foundation / Trustee**  
   - **Foundation** means Ark Foundation acting as trustee (or any successor trustee per this deed).

6. **Policies**  
   - Trustee-managed documents (e.g., Investment Policy, Distribution Policy) consistent with this deed and published in the public repository of record.

---

## Article 2 — Purpose, Mission, Core Values

1. **Purpose**  
   - To accumulate capital by owning broad baskets of productive businesses and, upon satisfying the Trigger Level, to provide **equal** periodic distributions to all persons, with a long-term orientation that preserves and grows the Trust’s real value.

2. **Mission & Core Values**  
   - **Longevity:** Design for centuries; prefer robust rules and automation.  
   - **Neutrality & Universality:** Equal distribution without means testing.  
   - **Transparency:** Public reporting, auditable processes, open documentation.  
   - **Fiduciary Duty:** Act solely in the interests of the global beneficiary class.

---

## Article 3 — Permitted Investments

1. **Business Ownership via Broad Funds**  
   - The Fund may hold **broad, low-cost, market-capitalization or rules-based index funds/ETFs** that primarily represent **ownership of operating businesses**.

2. **Cash & Cash Equivalents**  
   - Reasonable liquidity for operations, rebalancing, and distributions.

3. **Implementation**  
   - The Investment Policy may specify allowable tickers, rebalancing schedules, and thresholds provided they remain consistent with this Article and Article 4.

---

## Article 4 — Prohibited Investments

1. **Prohibited Asset Classes**  
   - **Commodities, land, and precious metals** (directly or via funds primarily holding such exposures).

2. **Other Exclusions**  
   - Instruments whose primary exposure is to the above (e.g., commodity pools, bullion funds).  
   - Derivatives whose primary purpose is speculation rather than prudent index replication, hedging, or liquidity management under policy.

3. **Interpretation**  
   - When in doubt, the Trustee must prefer holdings that clearly represent diversified **business ownership** rather than non-productive assets.

---

## Article 5 — Trigger & Distributions

1. **Trigger Condition**  
   - Distributions begin in the first fiscal month after **NAV ≥ ($15,000 × world population)**, expressed in **2024 USD** (see Article 1.2).

2. **Target Distribution Rate**  
   - **~0.3% of NAV per month** (≈3.6%/yr) as an operational target, subject to Article 5.4 and Article 5.5.

3. **Minimum Stipend**  
   - Aim to provide **not less than $50/month/person (2024 USD)** when the Trigger Level is satisfied, provided doing so does not reduce the Trust below the Trigger Level on a sustained basis.

4. **Sustainability Constraint**  
   - The Distribution Policy must **avoid materially compromising** the Trust’s ability to sustain real value over a long horizon.  
   - If market conditions would cause the Fund to fall materially below the Trigger Level, the Trustee may **temporarily reduce** the monthly percentage (while documenting rationale publicly) until conditions normalize.

5. **Universal & Equal**  
   - Distributions are **equal for every person** and not means-tested. Administrative practicality and legal compliance may require phased mechanisms; equality of the per-person amount remains the governing rule.

6. **Operationalization**  
   - The Distribution Policy will define cadence, delivery rails, KYC/AML compliance, and fallback procedures, with preference for open standards and verifiable processes.

---

## Article 6 — Governance & Fiduciary Duties

1. **Trustee Role**  
   - The Foundation serves as Trustee, owes **duties of loyalty, care, and impartiality**, and must act solely in the interests of the global beneficiary class.

2. **Policy Management**  
   - Trustee may adopt and revise Policies consistent with this deed. Changes must:  
     a. Be proposed and approved via public pull request;  
     b. Include a plain-language rationale mapping to deed constraints;  
     c. Be recorded in a changelog.

3. **Conflicts of Interest**  
   - Trustee and its agents shall avoid conflicts and disclose any unavoidable conflicts publicly with mitigation steps.

---

## Article 7 — Successor Trustee

1. **Resignation or Removal**  
   - The Foundation may resign on reasonable notice; it may be removed for cause per a process defined before execution in the Trust–Foundation Agreement and this deed’s final version.

2. **Successor Appointment**  
   - A successor trustee must expressly agree to this deed. If the incumbent custodian/broker cannot support the deed’s constraints, the Trustee must **promptly appoint** a compliant successor custodian and migrate assets.

---

## Article 8 — Custodian/Brokerage Controls

1. **Constraint Enforcement**  
   - Accounts shall be maintained with reputable institutions that can **enforce or attest** to the investment constraints (Articles 3–4).

2. **Failover Requirement**  
   - If an institution cannot or will not adhere to the constraints, the Trustee shall migrate to one that can, with public notice of timing and rationale.

3. **Automation & Auditability**  
   - The Trustee will prefer configurations enabling **automated, auditable** controls and publish non-sensitive attestations.

---

## Article 9 — Reporting & Transparency

1. **Public Metrics**  
   - Publish non-PII metrics (e.g., NAV estimate, world population source, distribution parameters) at a stable public endpoint (e.g., `/public/data/metrics.json`) with an accompanying schema and timestamp.

2. **Annual Summary**  
   - Provide an annual public summary including investment holdings by category, fees, and distribution statistics. Commission an independent review when feasible and publish a summary.

3. **Repository of Record**  
   - Keep the deed, policies, and relevant non-sensitive artifacts in a public repository with version history.

---

## Article 10 — Amendments & Irrevocability

1. **Amendments (Pre-Irrevocability)**  
   - Prior to the **Irrevocability Date**, this deed may be amended to improve clarity, legality, or implementation **without weakening the core constraints** in Articles 2–5 and 8–9, and only via public process with counsel review.

2. **Irrevocability**  
   - The deed becomes **irrevocable on the date that is 10 years after the Effective Date**. After that date, amendments are limited to:  
     a. Purely administrative or technical fixes that do **not** alter Articles 2–5 and 8–9 in substance; or  
     b. Changes **mandated by law** to maintain legality, implemented in the **least-deviation** manner and documented publicly.

3. **Effective Date**  
   - To be set at execution.

---

## Article 11 — Governing Law & Dispute Resolution

- To be selected with counsel prior to execution (e.g., a U.S. jurisdiction with well-developed trust law).  
- Include forum, venue, and dispute resolution mechanics in the final executed version.

---

## Article 12 — Severability

- If any provision is held invalid or unenforceable, the remaining provisions remain in full force and effect to the maximum extent permitted by law.

---

## Article 13 — Execution

This deed shall be executed by the settlor(s) and the initial trustee and take effect on the Effective Date.

---

### Change Log

- **v0.1 (Draft):** Initial public draft for comment; incorporates trigger formula, distribution target, prohibited assets, transparency, automation preference, successor trustee provisions, and 10-year path to irrevocability.
