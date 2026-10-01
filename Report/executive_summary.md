# Executive Summary — Marketing Performance Analysis & Growth Strategy

**Engagement:** Freelance data analysis for an e-commerce client
**Scope:** 6 months of paid search, paid social, and e-commerce sales data
**Objective:** Increase sales by 25% without increasing marketing budget

> *All figures below are presented as ratios and relative measures rather than absolute currency amounts, and campaign/ad names have been anonymized, to protect client confidentiality. The analytical approach and conclusions are unchanged from the original engagement.*

---

## 1. What Was Working

The paid search channel was substantially more capital-efficient than the paid social channel — roughly 3x the return per unit of spend — but received only a small fraction of total ad budget. Social carried the large majority of spend and drove most of the click volume, with a click-through rate more than double that of search, meaning top-of-funnel attention capture was not the problem.

## 2. What Was Not Working

Two issues stood out:

- **Efficiency decline:** both ad platforms showed a synchronized drop in return-on-spend starting roughly midway through the period, continuing through to the most recent month in the data. Because the decline appeared on two independent platforms at the same time, it pointed to a shared underlying cause (most likely creative fatigue and audience saturation) rather than a platform-specific issue.
- **Funnel leak:** a severe drop-off was found between cart additions and checkout initiation on the social platform — on the order of a 99% loss at that step. Notably, recorded purchases exceeded recorded checkout-starts, which is only possible if the checkout-tracking event itself is incomplete — so this was flagged explicitly as an unproven hypothesis (tracking gap vs. real friction) requiring further investigation, not assumed.

## 3. Winners and Losers

Drilling below account-level averages to the campaign, ad-set, and individual-creative level surfaced a pattern that aggregate numbers alone would have hidden: **roughly one in three ad-level line items with meaningful spend were returning less than they cost.** At the same time, a small number of campaigns and ad sets — particularly retargeting-based ad sets — were performing well above the account average and had room to absorb more budget.

A concrete creative-fatigue example was identified: one of the highest-spend ad creatives showed click-through rate falling by roughly two-thirds while cost-per-click simultaneously rose more than 10x, within the same month — a clear signal that the creative needed to be refreshed rather than continuing to receive spend.

## 4. Budget Reallocation Approach

A fully budget-neutral reallocation plan was built: total spend was held constant, with money moved from underperforming, high-spend campaigns into proven, scalable winners. Importantly, the highest-ROAS campaigns were **not** simply given the largest increases — campaigns with excellent ROAS but a small spend base were scaled conservatively (to avoid the efficiency erosion that typically comes from scaling paid search too quickly), while a campaign with a more moderate ROAS but already-proven ability to absorb significant scale received a larger increase. Two small test budgets were also carved out: one for an under-explored geographic market showing organic sales activity with zero paid support, and one for refreshing the identified fatigued creative.

## 5. Growth Target Feasibility

The math behind the growth target is exact: when spend is held flat, the required efficiency improvement is always mathematically equal to the sales growth target — a 25% sales increase at flat spend requires exactly a 25% improvement in return-on-spend. This reframes the question from "is 25% growth possible?" to "can this account realistically get 25% more efficient?"

Based on the evidence available, reallocating toward proven winners was estimated to close roughly a third to half of the required efficiency gap on its own. Closing the remainder depended on two factors that were not yet proven: whether the checkout funnel issue had a real, fixable cause, and whether the efficiency decline could be reversed through creative refresh rather than continuing. The recommendation was to treat the full growth target as the ambition, with a more conservative range as the defensible planning number — rather than promising the full target was guaranteed.

## 6. Deliverables

- Full written analysis across performance, campaign-level audit, budget plan, and growth feasibility
- A 7-page interactive Power BI dashboard (executive overview, channel comparison, campaign performance, ad-set/ad deep dive, funnel diagnostics, budget plan, management summary)
- A reusable DAX measures library
- A one-page management summary for stakeholder review

---

*This summary accompanies the sanitized analysis notebook and dashboard documentation in this repository. See `notebooks/Portfolio_Marketing_Analysis.ipynb` for the full reproducible analysis.*
