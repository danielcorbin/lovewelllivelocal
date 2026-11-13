# Love Well. Live Local.

Static website for Love Well Connections (lovewellconnections.com). Plain HTML, CSS and JavaScript. No build step.

## Files
- `index.html`: home page
- `local-partners.html`: partner directory with search, category, county and town filters
- `faq.html`: frequently asked questions for members and businesses
- `future-business-partners.html`: learn more about being a local partner (questions and answers)
- `partner-application.html`: form for businesses that want to join, with a logo upload. Set `FORM_ENDPOINT` in its script to your own form service address (for example a FormBackend form) so submissions and logos arrive by email. While it is empty, the form opens a ready-to-send email instead.
- `contact.html`: general contact form. Set `CONTACT_ENDPOINT` in its script to your own form service address (a separate FormBackend form for Love Well).
- `membership-terms.html` and `privacy-policy.html`: legal pages
- `robots.txt` and `sitemap.xml`: SEO files (they assume the site lives at https://lovewellconnections.com/)

## Editing partners
Open `local-partners.html` and find `var PARTNERS`. Each entry has a name, category, town, county, logo path, link, description and offer. Add a real logo by putting the image in a `logos/` folder and setting `logo: "logos/name.png"`. The partner list in the structured data near the top of the same file is for search engines, so update it when partners change.

## Publishing with GitHub Pages
1. Push these files to the root of a repository.
2. Repository Settings, Pages, deploy from the `main` branch, root folder.
3. To use lovewellconnections.com, add it under Custom domain and point the domain's DNS to GitHub Pages.

Checkout and member portal links go to Payhip and are unchanged.
