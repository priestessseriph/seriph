# Import report: Sacred Sensuality

Imported from https://tantra369.com (GoDaddy Website Builder, Starfield Technologies; Go Daddy Website Builder 8.0.0000) on 2026-10-28 with `openspace import url`.
Sources: page HTML, the sitemap. 27 requests.

## Summary

- **15** pages, **0** collection items in 0 collection(s)
- **5** media files (0.3 MB) downloaded into `media/`
- **1** redirects so old addresses keep working
- **75** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | Home | 2 | 3 |
| `/reviews` | `/reviews` | Sacred Sensuality | 2 | 2 |
| `/booking-request` | `/booking-request` | Sacred Sensuality | 2 | 2 |
| `/about` | `/about` | Sacred Sensuality | 2 | 2 |
| `/blog` | `/blog` | Sacred Sensuality | 2 | 2 |
| `/services` | `/services` | Sacred Sensuality | 2 | 2 |
| `/couples-retreat` | `/couples-retreat` | Sacred Sensuality | 2 | 2 |
| `/femme-services` | `/femme-services` | Sacred Sensuality | 2 | 2 |
| `/read-before-session` | `/read-before-session` | Sacred Sensuality | 2 | 2 |
| `/m/login` | `/m/login` | Sacred Sensuality | 2 | 2 |
| `/m/reset` | `/m/reset` | Sacred Sensuality | 2 | 2 |
| `/m/create` | `/m/create` | Sacred Sensuality | 2 | 2 |
| `/m/create-account` | `/m/create-account` | Sacred Sensuality | 2 | 2 |
| `/blog/f/what-led-me-here` | `/blog/f/what-led-me-here` | What led me here: beginning my tantra practice | 2 | 2 |
| `/blog/f/what-is-it-to-be` | `/blog/f/what-is-it-to-be` | What is it to BE? Awareness, presence & love | 2 | 2 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying GoDaddy Website Builder's CSS or code.

- The site's palette has no strong color (none found), so the Monochrome palette is used.
- Fonts on GoDaddy Website Builder: Cinzel / Source Sans Pro → pairing "Bricolage Grotesque & Geist" (Bricolage Grotesque / Geist), the closest curated match. Licensed fonts can be uploaded in Site Styles → Fonts.
- Type scale on GoDaddy Website Builder: Heading 1 is 3.9× body text. Density "comfortable" from the section heights.
- Fonts on GoDaddy Website Builder kept as they are (Cinzel, Source Sans Pro): free on Google Fonts, self-hosted with the site.
- Type scale on GoDaddy Website Builder (the live site, measured in a browser) kept: display 71px/46px, heading 1 71px/46px, body 18px/18px.
- Page rhythm on GoDaddy Website Builder (the live site, measured in a browser): content 1344px wide, sections padded 56px (40px on phones) — kept in Site Styles.

Design check: 0 error(s), 16 warning(s).

- warning (/): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/): “Home” has no clear call to action — nothing tells visitors what to do next.
- warning (/reviews): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/booking-request): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/about): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/blog): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/services): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/couples-retreat): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/femme-services): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/read-before-session): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/m/login): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- warning (/m/reset): “Sacred Sensuality” has no clear call to action — nothing tells visitors what to do next.
- … and 4 more: run Design check in Studio or `design_check` with Claude.

## Needs attention

### Custom code and embeds

- Site-wide scripts were found (3: Google Analytics / Tag Manager, img1.wsimg.com, googletagmanager.com). They were **not** copied: add what you still need (analytics, chat) in Settings → Advanced. GoDaddy Website Builder-specific scripts won't work here. _(site)_

### Links

- Text link to /m/bookings led to a page that wasn't imported; the link was removed. _(/, /reviews, /booking-request, /about, +11 more)_
- Text link to /m/account led to a page that wasn't imported; the link was removed. _(/, /reviews, /booking-request, /about, +11 more)_

## Redirects

Saved in `content/site.json` (`redirects`), published with the site:

| From | To |
| --- | --- |
| `/services/ola/services/meet-greet` | `/services/` |

## Not moved by the importer

- Online store, appointments and marketing tools.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://tantra369.com` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (GoDaddy Website Builder Domains, your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the GoDaddy Website Builder plan until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).

