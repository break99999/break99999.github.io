# break99999.github.io

Static GitHub Pages site for `www.acleanbreak.band`.

## Structure

- `index.html`: homepage and hand-edited post index
- `about.html`: about/bio page
- `merch.html`: merch page with a featured item layout
- `shows.html`: upcoming shows page
- `posts/`: individual blog posts as standalone HTML files
- `style.css`: shared site-wide styling
- `feed.xml`: manually maintained RSS feed
- `CNAME`: custom GitHub Pages domain

## New Post Checklist

1. Create a new HTML file in `posts/` using an existing post as a template.
2. Use `../style.css` and `../index.html`-style links inside post pages.
3. Add a new `<li>` entry to the post list in `index.html`.
4. Add a new `<item>` entry to `feed.xml`.
5. Update `lastBuildDate` in `feed.xml`.
6. Commit and push to publish through GitHub Pages.

## Updating Other Content

- Edit `about.html` for band bio, links, and general profile info.
- Edit `merch.html` for store links, item cards, and contact details.
- Edit `shows.html` for upcoming dates and venue information.
- Edit `style.css` for site-wide typography, spacing, and colors.

## Notes

- Navigation is duplicated across pages, so link changes need to be updated in each HTML file.
- Merch images should live in an `images/` folder if referenced from `merch.html`.
- RSS is fully manual, so the site homepage and feed should be updated together when publishing posts.
