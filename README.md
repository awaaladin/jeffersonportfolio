# jeffersonportfolio

This repository contains the static portfolio site for Emmanuel Jefferson (EJ). It is a single-file static site (`portfolio.html`) with inline styles and JS used for the personal portfolio at the root of this workspace.

Summary:
- Portfolio: `portfolio.html` — personal site, hero, projects, skills, experience and contact.
- SHACK360 (S360 Framework): the portfolio references two related repos:
  - Documentation: https://github.com/awaaladin/shark360_pkg-DOC (canonical docs & design)
  - Framework code: https://github.com/awaaladin/SHACK360_pkg (framework code + install)

SHACK360 summary (docs-first):
SHACK360 is a modular framework for S360chain — a peer-to-peer, file-backed chain combining Python orchestration
with an optional C++ hashing accelerator. The docs repository contains the DESIGN_DOCUMENT and MODULAR_INSTALL
instructions; follow those files for installation steps, configuration, and recommended deployment options.

How to publish this portfolio repository locally and push to GitHub (run these from the `portfolio` folder):

```bash
# initialize repo and push to your GitHub
echo "# jeffersonportfolio" >> README.md
git init
git add README.md portfolio.html
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/awaaladin/jeffersonportfolio.git
git push -u origin main
```

Notes:
- I cannot push on your behalf from this environment; run the commands above locally where your Git credentials are configured.
- If you want, I can add more project cards (linking to public repos) — tell me which repo names to include (for example: `shop`, `Trinity`, `GaX`).
