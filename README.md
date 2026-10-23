# Which Test Can I Run

Which kind of lift test can you actually run with your spend, conversions and set-up? Enter what you spend, how many conversions you get, and what you can control, and get your best available option, the reason for each of the five, and what to fix to open up a better one.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Options:** platform conversion lift, platform brand lift, manual holdout, geo test and pause test.
- **Verdict:** your best available option, or `no test yet`, with a fix list.
- **Manual holdout arithmetic:** with T conversions among people who see the ads and a holdout of share h, the holdout would have about C = T x h / (1 - h) conversions if the ads did nothing. The smallest visible lift is exp((1.960 + 0.842) x sqrt(1/T + 1/C)) - 1, at 95% confidence and 80% power.
- **Thresholds:** Meta conversion lift ($5,000 spend in the last year and 500 optimised conversions in 90 days with tracking in place), Meta brand lift ($30,000) and a geo rule of thumb (about $500,000 a year). All come from secondary sources and were checked on 2026-10-23, not from the platforms' own pages, and the page says so beside each. Google, TikTok and others are marked "check" because no threshold was verified.
- **Share:** a paper-ground PNG card, and the URL hash carries your answers.

Platforms change these rules without notice, so verify before you plan around them. A test you cannot run is not a reason to trust the dashboard. Pairs with holdout-sizer (the full plan) and lift-memo (reading the result).

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
