# Love Well. Live Local.

Static website for Love Well Connections (lovewellconnections.com). Plain HTML, CSS and JavaScript. No build step.

## Files
- `index.html`: home page, partner directory with search, category, county and town filters
- `membership-terms.html` and `privacy-policy.html`: legal pages
- `robots.txt` and `sitemap.xml`: SEO files (they assume the site lives at https://lovewellconnections.com/)

## Editing partners
Open `index.html` and find `var PARTNERS`. Each entry has a name, category, town, county, logo path, link, description and offer. Add a real logo by putting the image in a `logos/` folder and setting `logo: "logos/name.png"`.

## Publishing with GitHub Pages
1. Push these files to the root of a repository.
2. Repository Settings, Pages, deploy from the `main` branch, root folder.
3. To use lovewellconnections.com, add it under Custom domain and point the domain's DNS to GitHub Pages.

Checkout and member portal links go to Payhip and are unchanged.
