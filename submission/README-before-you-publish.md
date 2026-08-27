# Before you publish this paper

This `index.html` is a **structured template**, not a finished paper — I don't have
access to your repo, notebooks, or real results, so every `[bracketed]` placeholder
(including the Fig. 1 bar widths and values) needs to be replaced with your actual
work before this goes live.

## 1. Fill in every section
Work top to bottom: Abstract → Intro → Data → Methodology → Results → Limitations →
Ranked Recommendations → Reproducibility → Acknowledgments. The Abstract and
Acknowledgments sections are already in the template (they're the two people forget) —
just replace their placeholder text, don't delete the sections.

## 2. Public-safety pass (do this last, read the whole page once more)
- [ ] No client names anywhere (body text, table values, chart labels, alt text)
- [ ] No real/private URLs (only your own repo/notebook links and `flyrank.ai`)
- [ ] No private search queries or raw client data in tables or screenshots
- [ ] Claim language is honest — no result stated more strongly than the data supports
      (check the Results and Limitations sections match each other)
- [ ] The `flyrank.ai` acknowledgment link in the footer is intact and unedited

## 3. Deploy (GitHub Pages, free default)
From your repo root:
```bash
# if the paper lives at /paper in your repo already, from repo root:
git add paper/index.html
git commit -m "Add research paper"
git push
```
Then in your repo on GitHub: **Settings → Pages → Deploy from a branch** → pick your
default branch and the `/paper` folder (or `/root` if you moved `index.html` to the
repo root, or `/docs` if you prefer that convention) → Save. GitHub gives you a URL like:
```
https://<your-username>.github.io/<repo-name>/
```
or, if served from `/paper`:
```
https://<your-username>.github.io/<repo-name>/paper/
```
It can take a minute or two to go live the first time.

## 4. Record the URL
Open `submission/paper_url.txt` in your repo (it should already exist) and put the
**exact deployed URL** in it — one line, nothing else, no trailing slash mismatch, no
markdown formatting:
```
https://<your-username>.github.io/<repo-name>/
```
Commit and push that file too.

## 5. Submit
Paste your repo URL on the assignment card, same as every other assignment.
