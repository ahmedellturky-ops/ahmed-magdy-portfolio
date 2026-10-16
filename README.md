# Ahmed Magdy — Developer Portfolio

This is a standalone HTML portfolio prepared for static hosting.

## Files
- `index.html` — complete portfolio page. The CV PDF data is embedded in the page.

## Publish using GitHub + Vercel
1. Create a new **public** GitHub repository named `ahmed-magdy-portfolio`.
2. Upload `index.html` to the repository root (not inside another folder).
3. Open Vercel and import the new GitHub repository.
4. For a plain HTML site, use the static/Other configuration. No build command is needed; set the output/root directory to the repository root if Vercel asks.
5. Deploy, then open the generated URL and test the portfolio, CV download, and links.

Do not add a portfolio URL to the CV until the deployed URL is live and verified.

## Notes
- The page loads Inter and Space Grotesk from Google Fonts; the site still has system-font fallbacks.
- The contact form uses a `mailto:` fallback, not a backend form service.
