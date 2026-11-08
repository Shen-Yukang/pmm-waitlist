# PMM waitlist

The public intro page for PMM, the accountability ledger shared by people and Agents.

- `index.html` is the whole site: one self-contained file with no external scripts, fonts or styles. It switches between Chinese and English (button at the top right, `?lang=en` or `?lang=zh`, otherwise the browser language) and follows the system light or dark setting.
- The waitlist form posts straight to a Google Form. The form's address and the `entry` id of each question are in `GOOGLE_FORM` inside the page script. If the Google Form's questions or option texts change, update the page to match, or Google will reject submissions without the page noticing.
- Served with GitHub Pages from the `main` branch root.

The source of this page lives in the PMM repository at `docs/intro/index.html`; edit it there and copy it here.
