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

The provided file contains the seller record derived from the supplied publisher ID, pub-9404893474354911. Compare it with the exact snippet shown in AdMob before publication.

For a GitHub project site, the included file is at `/barons-of-crude-game/app-ads.txt`. AdMob instead requests `/app-ads.txt` on the developer website hostname. Either:

1. Configure a custom domain for this repository and serve this site at that domain root; or
2. Publish the file to the root organization Pages repository, `onvexalabs-dev.github.io`, without overwriting other games' seller records.

The organization-root repository has not been modified by this project. No custom domain has been invented or configured. See [Google's instructions](https://support.google.com/admob/answer/9363762).

## Required completion before commercial release

- Add a real service address and jurisdiction-specific required publisher disclosures in `imprint.html`. No address or registration number has been invented.
- The privacy policy is updated for optional AdMob rewards. Finalize audience, territories and account-side consent configuration before enabling production ads.
- Validate the final policies against the publisher's location, release territories, target audience and actual implementation. The draft does not constitute completed legal clearance.
- Verify support links and dates whenever data practices change.

Verification on 29 September 2026: the root https://onvexalabs-dev.github.io/app-ads.txt returns 200 and contains the supplied publisher record. The intended project privacy URL returns 404; pushing source alone does not publish it.
