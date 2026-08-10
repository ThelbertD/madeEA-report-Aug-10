# MadeEA — DM Setter Build Report

A single static page reporting the build state of the MadeEA Instagram DM
setter: status, release blockers, verification results and next steps, with
screenshots of both n8n workflows.

## Deploying

Plain static HTML — no build step, no framework, no dependencies.

- **Vercel:** import this repo at [vercel.com/new](https://vercel.com/new).
  Leave every build setting empty; `index.html` at the root is the whole site.
- **Anywhere else:** upload the three files. That's it.

## Updating

Edit `index.html` directly. The two `.webp` files are cropped screenshots from
the live n8n instance — replace them in place to refresh the diagrams.

## Contents

| File | |
|---|---|
| `index.html` | The report. Styles are inline; both light and dark themes are defined. |
| `setter.webp` | The IG DM Setter workflow, 15 nodes |
| `followup.webp` | The IG Follow-up workflow, 20 nodes |

The source workflows and their documentation live in the MadeEA Hub repo
under `n8n/`.
