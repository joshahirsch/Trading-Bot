# Trading Bot Dashboard

Auto-published paper-trading dashboard for the Kalshi signal engine.
Live site: https://joshahirsch.github.io/Trading-Bot/

Updated daily by the automated trading loop. Paper trading only - no real money.

## Password splash (casual deterrent only)

The live dashboard shows a lightweight front-end password screen before revealing
content. This is **not secure authentication**: GitHub Pages serves static public
files, so the password and all dashboard HTML live in the page source. Anyone
motivated can bypass it. It only discourages casual browsing. Access persists for
the browser tab session via `sessionStorage` until cleared.
