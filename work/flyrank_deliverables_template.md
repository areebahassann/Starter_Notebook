# FlyRank Case Study — Deliverables Template

> **Note:** This is a fill-in-the-blank template. Replace every `[bracketed]` placeholder
> with your actual project details, numbers, and findings before committing to `work/`.
> Do not publish this with placeholders still in it.

---

## 1. Paper — Abstract (edit your existing abstract to include this framing)

This work addresses a real content problem observed at **FlyRank**: `[state the specific
problem — e.g., "product pages ranking below expectations for target keywords due to
thin content and inconsistent internal linking"]`. Using `[your dataset — e.g., a sample
of N FlyRank client pages / N months of ranking data]`, we `[your method in one sentence
— e.g., "built a model to predict which on-page content signals correlate most with
ranking movement"]`. Our findings show `[headline result, one honest sentence — e.g.,
"content length alone was a weak predictor, but internal-link density explained X% of
variance in ranking change"]`. These results suggest `[practical implication for
FlyRank's actual workflow]`.

---

## 2. Paper — Introduction (add a paragraph like this near the top)

FlyRank, `[one line on what FlyRank does / the team's context]`, faces an ongoing
challenge: `[restate the problem in more detail — what was actually broken, slow,
unclear, or costly]`. This problem is the case study for this paper — not a
hypothetical or external dataset, but `[N records / pages / campaigns]` drawn directly
from FlyRank's own content pipeline. We frame our research question around this problem
as: **`[your research question, e.g., "Which on-page and structural signals best predict
ranking improvement for FlyRank's client pages?"]`**. The remainder of this paper
develops a method to answer that question and reports what we found — including where
the method fell short.

---

## 3. Notebook — Closing Markdown Section: 5-Minute Demo Outline

*(Paste this as the final markdown cell in your last notebook.)*

### 🎤 Week 8 Showcase Demo Outline (5 min, optional)

**1. Question (30 sec)**
`[The one-sentence question you set out to answer about the FlyRank content problem]`

**2. Method (1 min)**
`[2-3 sentences: what data you used, what model/analysis you ran, and why that approach]`

**3. Chart (1.5 min)**
`[Insert/describe the ONE chart that best tells the story — e.g., a bar chart of
predicted vs. actual ranking change, or a feature-importance plot]`
```python
# reference to the cell above where this chart was generated
```

**4. Honest Result (1 min)**
`[State what actually happened — including limitations. E.g., "The model explained 41%
of variance — useful directionally, but not reliable enough for automated decisions
without more data."]`

**5. Recommendation (1 min)**
`[One concrete, actionable next step for FlyRank — e.g., "Prioritize internal-linking
audits on pages with >3 months of stagnant rank before content rewrites."]`

---

## 4. Shareable Cuts

*(Paste this markdown cell directly under the demo outline above.)*

### 📱 Short Social Post (methodology-focused)

> Spent the last few weeks digging into a real content problem at FlyRank:
> `[problem in plain language]`. Pulled `[N]` `[data type]` and tested whether
> `[method/signal]` could predict `[outcome]`. Turns out `[one surprising or honest
> takeaway]` — not the clean answer I expected, but a useful one. Full writeup: `[link]`
> #dataanalysis #seo `[other relevant tags]`

### 💼 Employer-Facing Summary (3 sentences)

> I built `[what you built — e.g., "a predictive model for content ranking signals"]`
> using `[what data — e.g., "FlyRank's historical page performance and content
> metadata"]`. It showed `[what it showed — one honest, specific finding, including any
> limitation]`. The result `[practical takeaway — e.g., "gives FlyRank a prioritization
> heuristic for content audits rather than a fully automated ranking predictor"]`.

---

## Checklist before committing to `work/`

- [ ] Abstract and intro edited in the actual paper file (not this template)
- [ ] Demo outline pasted as final markdown cell in the last notebook
- [ ] Shareable cuts pasted as markdown cell directly under the demo outline
- [ ] All `[placeholders]` replaced with real numbers/findings
- [ ] Chart referenced in demo outline actually exists in the notebook above that cell
- [ ] Repo pushed and deployed URL confirmed working
