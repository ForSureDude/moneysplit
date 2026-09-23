# MoneySplit 2.0

A static, mobile-first money allocation calculator.

## Files
- index.html — calculator, chart, dark mode, presets, download, share and print/PDF.
- about.html — about page.
- privacy.html — starter privacy policy; customize before advertising.
- terms.html — starter terms; customize before launch.

## Run locally
Open index.html in a browser.

## Deploy
Recommended: GitHub + Cloudflare Pages.
1. Create a public GitHub repository named `moneysplit`.
2. Upload these files to the repository.
3. In Cloudflare: Workers & Pages → Create application → Pages → Import an existing Git repository.
4. Choose the GitHub repository.
5. Production branch: `main`.
6. Build command: `exit 0`.
7. Output directory: `/` (or the repository root).
8. Deploy.

## Before advertising
- Buy/connect a custom domain.
- Replace placeholder contact information.
- Review privacy/terms for your actual business and advertising providers.
- Add original guides/articles and clear navigation.
- Apply to Google AdSense when the site is live and has useful original content.
- Add the actual AdSense code only after approval/instructions from Google.
- Consider a consent-management solution where required.

## Notes
The MVP has no database and performs calculations in the visitor's browser. The share feature stores the calculation in the URL fragment. The download button creates a CSV locally.
