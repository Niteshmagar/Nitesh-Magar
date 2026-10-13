# Preservation-first CMS starter

- `original-blogger-template.xml` is an exact copy of the uploaded Blogger theme. It is NOT a GitHub Pages-ready `index.html`.
- `admin/index.html` and `admin/config.yml` are a Decap CMS starter only. The GitHub OAuth proxy and repository must be configured before login works.
- CMS posts are saved as Markdown under `posts/`. GitHub Pages does not automatically display them on an existing static HTML site; a rendering/build integration is still required.
- Existing GitHub Pages site files should remain unchanged. Do not replace your existing `index.html` with the Blogger XML.
- To complete a pixel-faithful conversion and preserve actual post bodies, video embeds and external links, supply the currently deployed GitHub repository files and Blogger post export. A Blogger theme alone does not contain all posts or runtime widget data.
