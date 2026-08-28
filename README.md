# eunosia.cl

Landing page for [Eunosia](https://eunosia.cl), a clinical AI project focused on emergency medicine.

## Status

**In development — not a product.** There are no clinical deployments, no open pilots, no commercial availability, and no contact channel. The site exists as a technical record of the design and of the open-source research that came out of it.

The previous commercial version of the site is preserved on the `archive/commercial-site` branch.

## About

Eunosia explores AI tooling designed to run inside hospital emergency departments. It targets clinical Spanish (es-CL) and is architected for on-premise deployment — clinical data would never leave the institution.

Areas of work:

- **Clinical copilot** — inline autocompletion and contextual suggestions inside the EMR via a browser extension.
- **Disposition classification** — structured prediction of patient destination (discharge, observation, admission, ICU, transfer).
- **Diagnostic coding** — automatic ICD-10 coding from free-text clinical notes.
- **Demand forecasting** — patient volume and occupancy prediction.
- **Clinical NLP** — entity extraction, normalization, and segmentation of hospital free text.

The architecture is hybrid: classical models for structured decisions, language models for clinical text generation, with RAG over institutional protocols and clinical guidelines.

Published work lives in the open-source repos linked from the site: [neurogen](https://github.com/nicoveraz/neurogen) and [urgencias-core](https://github.com/nicoveraz/urgencias-core).

## Stack

Single-file vanilla HTML + CSS + JS. No build step, no dependencies. Dark/light theme with system preference detection.

## Development

Open `index.html` in a browser.

## Deployment

GitHub Pages on `main` with a custom domain via `CNAME`.
