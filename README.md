# Hex Color Picker support site

This is a no-build, tracker-free static support site for GitHub Pages. It includes the Support, Privacy Policy, and Terms links required by the app and App Store listing.

## Before publishing

Settled on 2026-09-12 and already written into the HTML:

- Legal name — **Meral Demircioğlu**, on all three pages and in every footer.
- Effective date — **2026-09-12**. Bump it if the pages go live materially later.
- Email provider — **Google (Gmail)**.
- Support-email retention — **six months**.
- Public business address — **deliberately omitted.** The address line was removed
  from `terms.html` rather than left blank. If you later register a business, or
  an EU trader disclosure obligation applies to you, put the line back.

- Support and privacy mailbox — **mdappssupport@gmail.com**, one inbox for both.
  It is deliberately not app-specific so later apps can share it.

No placeholders remain.

Read the policy carefully after the app is complete. It must match the shipped
SDKs, backup behavior, RevenueCat configuration, and legal obligations. This
template is not legal advice.

## Publish free with GitHub Pages

1. Create a new **public** GitHub repository, for example `hex-color-picker-support`.
2. Copy the contents of this `SupportSite` folder to the root of that repository.
3. On GitHub, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for GitHub to show the public HTTPS address, usually `https://meraldemircioglu.github.io/hex-color-picker-support/`.
5. Put `.../privacy.html` in App Store Connect’s Privacy Policy URL field, and use the site root or `.../index.html` for the Support URL. Add the same Privacy link inside the app.

Optionally use a custom domain after publishing and enforce HTTPS in GitHub Pages settings. Do not place private files, analytics scripts, or secret keys in the public repository.
