# Import report: River Deep

Imported from page.zip on 2026-11-17 with `openspace import html`.
Sources: the page's HTML and CSS. 0 requests.

## Summary

- **3** pages, **0** collection items in 0 collection(s)
- **0** media files (0.0 MB) downloaded into `media/`
- **0** redirects so old addresses keep working
- **9** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | Descend into your depths. | 8 | 18 |
| `/integrated-man` | `/integrated-man` | The Integrated Man | 7 | 15 |
| `/resources` | `/resources` | For the road between gatherings. | 7 | 12 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying the original site's CSS or code.

- Brand color #d0612a (the site's accent color).
- Fonts couldn't be read; pairing "Fraunces & Hanken Grotesk" is a neutral default.
- Type scale on the original site: Heading 1 is 2.4× body text. Density "comfortable" from the section heights.
- The contrast solver adjusted 8 color pairing(s) so every section theme meets WCAG AA (e.g. light accent-hover, light accent-pressed).

Design check: 0 error(s), 6 warning(s).

- warning (site): Your custom accent color is hard to read in the light theme: it needs 3:1 against surface. It's adjusted automatically when published.
- warning (/): “Access” jumps from Heading 1 to Heading 3, skipping a level.
- warning (/): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/integrated-man): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/resources): “For the road between gatherings.” has no clear call to action — nothing tells visitors what to do next.
- warning (/resources): Four sections in a row use the light color theme, so the page reads as one long block.

## Needs attention

### Links

- Link to /integrated-man.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/)_
- Link to /resources.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/)_

## Not moved by the importer

- Scripts, animations and anything rendered only by JavaScript (try `--render` for script-built pages).
- Server-side features: shops, logins, search, comments.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://site.openspace.invalid` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the old hosting until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).


## Designed sections

No sections were made into designer components.

Sections that use OpenSpace's own section designs instead:

- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /integrated-man: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /integrated-man: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /integrated-man: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /integrated-man: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /integrated-man: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /integrated-man: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /integrated-man: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /resources: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
