# Overview

This repository is used for maintaining the SDMX-ML messages specifications.

This includes:
* Normative documentation and XSD schemas for the SDMX-ML structure, data, metadata and registry interface messages
* Samples for core structures including Data Structure Definition, Code List and Concept Scheme
* Samples illustrating VTL and geospatial structures
* Data message samples

To test the samples, copy the ‘samples’ and ‘schemas’ folders into the same local directory.

The schemas are published to https://xml.sdmx.org

## Repository Structure

-   `docs/` — Markdown content pages for the SDMX-ML specification.
-   `mkdocs.yml` — MkDocs configuration integrating this component into the
    `sdmx-docs` site.

## Version Branches

Each release of this component is maintained on a dedicated branch following the
pattern `X.Y.x` (e.g., `3.1.x`). The branch tracked by the
[`sdmx-docs`](https://github.com/sdmx-twg/sdmx-docs) parent repository is
declared in `.gitmodules` at the root of that repo. Switching the tracked branch
in the parent repository is how a new version of this component is published on
the documentation site.

## Formatting Conventions

For Markdown and MkDocs formatting conventions that apply to content in `docs/`,
see the [`sdmx-docs` README](https://github.com/sdmx-twg/sdmx-docs#readme).

