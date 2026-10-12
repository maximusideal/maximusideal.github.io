# MaximusIdeal website

A small Astro site for GitHub Pages.

## Pages

- Home: `src/pages/index.astro`
- Blog: `src/pages/blog/index.astro`
- Projects: `src/pages/projects.astro`
- About: `src/pages/about.astro`

The shared header and page layout are in `src/layouts/PageLayout.astro`.
The stylesheet is `src/styles/site.css`.

## Local development

```sh
npm install
npm run dev
```

## Blog posts

Add a Markdown file to `src/content/blog/`, using the existing samples as templates.
Each post needs a title, date, category, and excerpt in frontmatter.
The blog index lists the posts newest first, and titles open individual post pages.

Push to `main` to deploy using GitHub Actions (Settings → Pages → GitHub Actions).
