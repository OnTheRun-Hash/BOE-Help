# Sullivan County Voter Help — Counter Pilot v2

A **small, restrained, customer-facing NFC + QR concept** to show the Sullivan County Board of Elections. Not an official county publication and not yet approved for visitors.

## Files

- `index.html` — phone-first landing page with four popular services above the fold and a collapsible directory for the rest.
- `config.js` — the official government destinations, display copy, public office phone/address, and `reviewed` flag.
- `editor.html` — local-only link editor; do not upload it to public hosting.
- `COUNTER_SIGN.html` — printable mockup with empty NFC and QR areas until the final web address is approved.
- `PRESENTATION_NOTE.txt` — a low-key 20-second demonstration script.

## Recommended demonstration

1. Open `index.html` on an iPhone in a browser, keeping `config.js` next to it, or host on a temporary **office-approved** testing domain.
2. Select registration or polling place; show that it opens an official NY State destination.
3. Switch to Spanish; demonstrate the visible navigation adapts (destination government pages manage their own translations).
4. Show the printable `COUNTER_SIGN.html` and explain the NFC tag and QR will use **one stable final HTTPS URL**.
5. Ask for approval to test one counter sign. Keep the pilot supervised.

## Publish safely

- Obtain written confirmation from supervisor, election-office management, communications/IT, and accessibility/language reviewers before public display.
- Review each URL, description, and Spanish-language translation. Avoid the county seal or a claim of official endorsement until authorized.
- For a sanctioned rollout, host only `index.html` and `config.js` on an authorized HTTPS domain. Do not host `editor.html`.
- Publish an accessible, publicly reachable URL before creating the final QR image and NTAG URL record.
- Check the NFC/QR destination using an unauthenticated mobile phone on cellular data, and ensure the posted tag cannot be quietly replaced.
- Keep links current. Do not hardcode election dates, voter eligibility advice or ballot deadlines.
- The hub uses no analytics, cookies, accounts, passwords, forms, sensitive voter data or external script libraries. Its search operates locally in the browser.

Primary official sources checked 2026-10-13:
- https://www.sullivanny.gov/Departments/Elections
- https://www.sullivanny.gov/Departments/Elections/EarlyVoting
- https://elections.ny.gov/register-vote
- https://elections.ny.gov/request-ballot
- https://voterlookup.elections.ny.gov/
