# Easy Thumbnail Editor

Easy Thumbnail Editor is a static browser-based image editor for thumbnail, profile, store, and app listing assets. It supports live previews, manual resizing, drag positioning, file conversion, and 3x3 image splitting.

## Main Features

- Browser-local image upload and drag-and-drop editing
- Manual X/Y position, width, height, and scale controls
- Auto ratio fitting with live preview
- YouTube profile image preview
- Instagram, X/Twitter, TikTok, Discord, and Steam profile previews
- Instagram, X/Twitter, and TikTok 3x3 converter export
- Steam Store asset sizes and preview layouts
- Google Play listing preview with app icon and screenshots
- ID photo resizing with px/cm, DPI, quality, and file size controls
- JPG, PNG, and WEBP export
- White, ivory, and dark themes
- English and Korean UI support

## SEO and AdSense Preparation

Included files:

- `index.html`
- `privacy.html`
- `terms.html`
- `contact.html`
- `robots.txt`
- `sitemap.xml`

Before submitting to Google AdSense or Search Console:

1. The default public URL is set to `https://ezeditor.org/`. Replace it later if you connect a custom domain.
2. Add your AdSense publisher code only after your AdSense account provides it.
3. If AdSense requires `ads.txt`, create it with the exact seller line provided by AdSense.
4. Submit `https://your-domain.com/sitemap.xml` in Google Search Console.
5. Verify the live domain uses HTTPS and all footer links open correctly.

## Deploying to GitHub Pages

1. Create a GitHub repository, for example `easy-thumbnail-editor`.
2. Upload all files in this folder to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select the `main` branch and `/root`, then save.
6. Wait for GitHub Pages to publish the site.
7. Replace `https://ezeditor.org/` in `index.html`, `robots.txt`, and `sitemap.xml` if you connect a custom domain.
8. If using a custom domain, add a `CNAME` file containing only that domain, then configure DNS in your domain provider.

## Local Git Commands

Run these commands after creating the GitHub repository:

```bash
git init
git add .
git commit -m "Initial Easy Thumbnail Editor site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```
