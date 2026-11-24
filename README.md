# xCH VPN privacy-policy website

A self-contained static privacy policy page for **xCH VPN (`com.buchu.rvpn`)** by BUCHU. The page uses inline CSS/SVG, system fonts, and no JavaScript, cookies, analytics, or external assets.
Public privacy contact: **su.dev.x51@gmail.com**.

## Publish with GitHub Pages

Repository: `https://github.com/XenonCR/RVPN`

Only this privacy-policy website belongs in this public repository. Keep the Android app source, APKs, AABs, Firebase configuration, keystore, and signing password files strictly private.

1. Upload `index.html`, `.nojekyll`, `LICENSE`, and `README.md` to the `main` branch at the repository root. You do not need npm, a build command, or GitHub Actions.
2. Open **Settings → Pages → Build and deployment** in `https://github.com/XenonCR/RVPN`.
3. Choose **Deploy from a branch**, then **main** and **/(root)**. Save.
4. Enable **Enforce HTTPS** when available and wait for GitHub’s deployment to finish.
5. Open the published URL and confirm the privacy policy and contact email load without signing in:

`https://xenoncr.github.io/RVPN/`

Use that URL in Google Play Console’s **Privacy Policy** field (and in the app’s About screen). Update the effective date at the top of `index.html` whenever the policy changes.

References:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://support.google.com/googleplay/android-developer/answer/10144311
