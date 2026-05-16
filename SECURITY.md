# Security Policy

## Current security model

TokSignal is currently a static browser based app. Uploaded CSV files and pasted analytics are processed locally in the browser.

## Do not commit

Never commit API keys, TikTok client secrets, OAuth tokens, Stripe keys, cookies, or private user exports.

## Reporting issues

Open a private security advisory on GitHub if available, or contact the maintainer through the links in `SUPPORT.md`.

## Future TikTok API note

When TikTok OAuth is added, the token exchange must happen on a backend such as Netlify Functions. Client secrets must not be stored in `index.html` or any public JavaScript file.
