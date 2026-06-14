# GitHub Pages Deploy Checklist

## Required Before Upload

- Create a GitHub repository.
- Upload every file in this folder to the repository root.
- Enable GitHub Pages from `Settings > Pages`.
- Confirm the site opens with HTTPS.

## Replace Before AdSense Review

Replace these placeholders after the final URL is known:

- `https://example.com/` in `index.html`
- `https://example.com/sitemap.xml` in `robots.txt`
- all `https://example.com/...` URLs in `sitemap.xml`

If the GitHub Pages URL is used without a custom domain, it usually looks like:

```text
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/
```

If a custom domain is used, create a `CNAME` file with one line:

```text
your-domain.com
```

## AdSense Notes

- Add the AdSense script only after Google gives you the publisher code.
- Add `ads.txt` only with the exact line provided by AdSense.
- Keep `privacy.html`, `terms.html`, and `contact.html` linked in the footer.
- Submit `sitemap.xml` in Google Search Console after the site is live.
