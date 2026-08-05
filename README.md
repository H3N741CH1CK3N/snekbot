# SnekBot Legal Site

This folder contains a standalone static website for GitHub Pages.
The image files `SNEKBGTOP.jpg`, `main1.png`, `main2.png` and `main3.png`, all eight HTML pages and `styles.css` must be uploaded together.

## Publishing

1. Create a new public GitHub repository named `snekbot-legal`.
2. Upload the **contents** of this folder to that repository.
3. In GitHub, open `Settings` → `Pages` and select `Deploy from a branch`.
4. Select branch `main`, folder `/ (root)`, then save.
5. Open and verify every published page in a browser.

Then add the published URLs to the bot's `.env` file:

```env
PRIVACY_POLICY_URL=https://YOUR-NAME.github.io/snekbot-legal/privacy.html
TERMS_OF_SERVICE_URL=https://YOUR-NAME.github.io/snekbot-legal/terms.html
```

The default URLs open the German GDPR version. The flag buttons link to the
corresponding English translations (`index-en.html`, `privacy-en.html`,
`terms-en.html` and `contact-en.html`).

Never upload `.env`, tokens, passwords, databases or bot logs.
