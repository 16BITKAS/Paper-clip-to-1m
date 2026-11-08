# Flip to $1M

A single-page dashboard for a reselling ledger. It shows the bankroll, what is listed, and the doubling ladder from a $10.40 CD lot toward $1M.

Open `index.html` in a browser. There is no build step and no external dependencies. On GitHub Pages the page is served from the repository root: https://16bitkas.github.io/Paper-clip-to-1m/

## Update the numbers

All figures, copy, and ledger rows live in the `DATA` object near the top of `index.html`. Edit that object and refresh. The source export is `data/ledger.csv`.

Light mode is the default. The header toggle stores the choice in `localStorage` under `flip-theme`.
