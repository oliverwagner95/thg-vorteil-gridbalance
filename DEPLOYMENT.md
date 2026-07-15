# Deployment Control

Live domain: https://vorteil.gridbalance.de

GitHub repository: https://github.com/oliverwagner95/thg-vorteil-gridbalance

GitHub Pages:

- Source: `main` branch, repository root `/`
- CNAME: `vorteil.gridbalance.de`
- HTTPS enforced: yes
- DNS target: `oliverwagner95.github.io`

Operational notes:

- This repository currently contains the built static output, not the original app source.
- Visual changes can be deployed by replacing the built files and pushing to `main`.
- For larger changes, recover or rebuild a source project first, then publish the static build here.
- Keep `CNAME` in the repository root so the custom domain remains attached.

Control check:

- Local control restored in OpenClaw workspace on 2026-07-15.
