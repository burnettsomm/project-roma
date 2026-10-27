# Walk-in Count

A phone web app for counting inventory by voice and turning the counts into the corporate upload worksheet.

- **Sites:** upload each site's inventory worksheet (.xlsx or .csv) and switch between sites from the top bar.
- **Count:** tap Start and speak, for example "egg patty 4 cases 3 each". Say "area frozen" to set the area and "scratch that" to remove the last line. Hands-free speech works in Chrome on Android and Safari on iPhone.
- **Review:** flags counts over 3 cases, items it couldn't match, best guesses to confirm, and items that sit in more than one worksheet row (you pick the slot).
- **Export:** writes Quantity (cases) and Break Quantity (each) into the site's worksheet, keeping every other column and the row order exactly as uploaded.

Everything is stored in the phone's browser. Nothing is sent to a server.

Served with GitHub Pages from the `gh-pages` branch. `xlsx.full.min.js` is SheetJS 0.18.5 (Apache-2.0).
