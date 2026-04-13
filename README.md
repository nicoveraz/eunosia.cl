# eunosia.cl

Landing page for [Eunosia](https://eunosia.cl), a clinical AI platform focused on emergency medicine.

## About

Eunosia builds AI tools designed to work inside hospital emergency departments. The platform targets clinical Spanish (es-CL) and is architected for on-premise deployment — no patient data leaves the institution.

Key areas:

- **Clinical copilot** — inline autocompletion and contextual suggestions inside the EMR via a browser extension.
- **Disposition classification** — structured prediction of patient destination (discharge, observation, admission, ICU, transfer).
- **Diagnostic coding** — automatic ICD-10 coding from free-text clinical notes.
- **Demand forecasting** — patient volume prediction with seasonal epidemiological variables.
- **Clinical NLP** — entity extraction, normalization, and segmentation of hospital free text.

The architecture is hybrid: classical models for structured decisions, language models for clinical text generation, with RAG over institutional protocols and clinical guidelines.

## Stack

Single-file vanilla HTML + CSS + JS. No build step, no dependencies. Dark/light theme with system preference detection.

## Development

Open `index.html` in a browser.

## Deployment

GitHub Pages on `main` with a custom domain via `CNAME`.
