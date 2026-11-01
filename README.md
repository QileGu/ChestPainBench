# ChestPainBench Project Page

This repository contains the public-facing project page for **ChestPainBench: Evaluating LVLMs for Multimodal Clinical Reasoning in Chest Pain**.

The page presents the research motivation, benchmark design, evaluation framework, principal findings, authorship information, and ethical constraints. It intentionally does **not** include clinical data, case-level model outputs, API credentials, model weights, or the internal evaluation codebase.

## Preview locally

From the repository root, run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Repository structure

```text
.
|-- index.html
|-- assets/
|   |-- styles.css
|   |-- construction-pipeline.png
|   `-- evaluation-framework.png
|-- .gitignore
|-- .nojekyll
`-- README.md
```

## Before publishing

- Confirm with the supervising professor and co-authors that the figures may be publicly posted.
- Confirm the final author list, affiliations, manuscript status, and preferred contact link.
- The manuscript PDF is intentionally excluded until public distribution is authorized.
- Keep all clinical source data, patient-level questions, case-level model outputs, and internal code outside this repository.

## GitHub Pages

After review, create a public GitHub repository named `ChestPainBench`, push this folder to the `main` branch, and enable GitHub Pages from the repository root.

The resulting URL will normally be:

```text
https://YOUR-USERNAME.github.io/ChestPainBench/
```

## Content status

All scientific statements and numerical results on the page are drawn from the supplied final manuscript. The clinical data are not distributed because of privacy, ethical, and institutional restrictions.

All rights reserved unless otherwise noted.
