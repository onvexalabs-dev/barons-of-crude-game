# Barons of Crude legal site

Static HTML/CSS, no build step, no scripts or tracking. Prepared for:
`https://github.com/onvexalabs-dev/barons-of-crude-game.git`

Publisher: **Manfred Uschan**. Contact: **onvexalabs@gmail.com**.

## Publish

Push these files to the repository root. Enable GitHub Pages with **Deploy from a branch → main → /(root)**. Expected URLs once Pages is enabled:

- `https://onvexalabs-dev.github.io/barons-of-crude-game/`
- `https://onvexalabs-dev.github.io/barons-of-crude-game/privacy.html`
- `https://onvexalabs-dev.github.io/barons-of-crude-game/terms.html`
- `https://onvexalabs-dev.github.io/barons-of-crude-game/support.html`

The repository being populated does not itself guarantee that GitHub Pages has been enabled. Verify actual HTTP responses before putting links in Play Console.

## app-ads.txt root requirement

The provided file deliberately contains no active seller record because the AdMob publisher ID is missing. Replace the commented example with the exact line from your AdMob account.

For a GitHub project site, the included file is at `/barons-of-crude-game/app-ads.txt`. AdMob instead requests `/app-ads.txt` on the developer website hostname. Either:

1. Configure a custom domain for this repository and serve this site at that domain root; or
2. Publish the file to the root organization Pages repository, `onvexalabs-dev.github.io`, without overwriting other games' seller records.

The organization-root repository has not been modified by this project. No custom domain has been invented or configured. See [Google's instructions](https://support.google.com/admob/answer/9363762).

## Required completion before commercial release

- Add a real service address and jurisdiction-specific required publisher disclosures in `imprint.html`. No address or registration number has been invented.
- The current privacy policy accurately describes the **ad-free development build**. Update it before enabling AdMob, including actual SDK data categories, purposes, partners, retention and applicable choices.
- Validate the final policies against the publisher's location, release territories, target audience and actual implementation. The draft does not constitute completed legal clearance.
- Verify support links and dates whenever data practices change.
