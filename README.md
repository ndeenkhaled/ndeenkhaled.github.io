# Nadine Khaled — Portfolio Website Starter

A responsive, static architecture + BIM portfolio starter with a warm brown and cream visual identity.

## Files
- `index.html` — page content and structure
- `styles.css` — visual design, layout, and responsive behavior
- `script.js` — small mobile navigation interaction and current year
- `assets/` — put your project images here

## Preview locally
Open `index.html` in your browser. The fonts load from Google Fonts when you have an internet connection; system fallback fonts are included.

## Before publishing
1. Replace the three sample project compositions with your own images and captions.
2. Update your About paragraph and skills so every statement matches your actual experience.
3. Replace `YOUR.EMAIL@example.com` with your professional email.
4. Replace the LinkedIn and Behance links with your actual profile URLs.
5. Check all project titles, dates, roles, software, and credits.
6. Add image alt text for every real project image.

## Replace a sample project image
For example, replace the contents of this link in `index.html`:
```html
<a class="project-image image-urban" href="#contact" aria-label="Add your urban design project details">
  ...
</a>
```
with an image such as:
```html
<a class="project-image" href="assets/project-01.jpg" target="_blank" rel="noreferrer" aria-label="Open project image">
  <img src="assets/project-01.jpg" alt="Site analysis and concept for [project name]">
  <span class="image-index">01 — DESIGN / URBAN</span>
  <span class="image-open">↗</span>
</a>
```
Then add this rule to `styles.css`:
```css
.project-image img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```
Repeat for each project. For a polished portfolio, export project images as compressed JPG/WebP, ideally around 1600–2000px wide and usually under 500 KB each.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new **public** repository named exactly `YOUR-USERNAME.github.io`.
3. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder to the repository root (not the ZIP file itself).
4. In the repository, open **Settings → Pages** and choose the publishing source/branch if prompted.
5. Visit `https://YOUR-USERNAME.github.io` after publishing finishes.

GitHub Pages is free for public repositories. Publishing may take a few minutes. You can also use Netlify or Cloudflare Pages free static hosting if preferred.

## Suggested first content pass
Prioritize 3 strong case studies rather than many small thumbnails:
- One architectural design project: brief, site/context, concept, plans/sections, final views.
- One BIM / technical project: model views, drawing sheets, details, and your exact contribution.
- One research / analysis project: site, climate, material, identity, or sustainability.

Be clear about what was your work, what was team work, and which images or drawings you are allowed to publish.
