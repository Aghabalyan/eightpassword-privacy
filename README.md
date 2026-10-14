# 8Pass Privacy Policy

A responsive, single-page Privacy Policy website for 8Pass (formerly 8Password). It is ready to publish with GitHub Pages and has no build step or external dependencies.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named `eightpassword-privacy`.
2. Upload `index.html` and `README.md` to the top level of the repository.
3. Open the repository's **Settings**.
4. In the sidebar, select **Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Choose the `main` branch and the `/(root)` folder, then select **Save**.
7. Wait a few minutes for GitHub to publish the site.

The expected address is:

```text
https://aghabalyan.github.io/eightpassword-privacy/
```

## Add the URL to App Store Connect

After the site is live:

1. Open the app in App Store Connect.
2. Add the published address to the **Privacy Policy URL** field.
3. Use the same address for the in-app Privacy Policy link.
4. Confirm the page opens without requiring a sign-in.

The policy links to Apple's Standard EULA at:

```text
https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
```

## Customize before publishing

- Review the policy against the App's actual behavior before publishing.
- If the App's data practices change, update the relevant sections and the effective date in `index.html`.
- The contact address currently used is `8pass.vault@gmail.com`.

## Preview locally

Open `index.html` in any web browser. No installation or build is required.

## Important

This template is general information, not legal advice. The published policy should accurately describe the current App, its integrations, and its data handling.
