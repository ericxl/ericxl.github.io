# CLAUDE.md

Personal site for Xiaoyong (Eric) Liang, deployed to GitHub Pages at https://ericxl.github.io/ from the `main` branch of `ericxl/ericxl.github.io`.

## Conventions

- **Last updated stamp.** Whenever you make a content change to `index.html` (bio, papers, links, etc. — not trivial whitespace), update the `<p class="updated">Last updated: Month YYYY</p>` line at the bottom of `index.html` to the current month and year. Month is spelled out (e.g. "April 2026"), not abbreviated. Purely stylistic/CSS-only tweaks do not need to bump it.
- **Vitæ employment type.** Default (full-time, internship, cofounder, etc.) renders with no badge. Add a small `<span class="cv-type">Contract</span>` after the company name *only* for contractor roles. No other employment types get a badge.
- **Vitæ company logos.** Each experience `<li>` begins with `<img class="cv-logo" src="logos/<slug>.png" alt="" />`. When adding a new role, download the company logo from LinkedIn (or the company site) into `logos/` using a lowercase slug (e.g. `anthropic.png`, `human-data-company.png`). Keep `alt=""` — the company name is already in the adjacent text, so the logo is decorative.
