# discover

Client discovery forms hosted via GitHub Pages.

Each client has their own subdirectory with an `index.html` form. Forms are pure
client-side: they save in-progress answers to `localStorage` and produce a
downloadable Markdown file on submit.

## Structure

- `<client-slug>/index.html` — the client's form (e.g. `galgal/`)
- Source of truth for the form template lives in the private
  [`consulting`](https://github.com/Communication-Band/consulting) repo,
  under `shared/forms/discovery-questionnaire.html`. This repo is the published
  copy.
