# Admins hub

Static site for `admins.demark.com.ng`. No build step.

- `index.html` is the list of admin sites.
- `mm-portfolio/index.html` is the admin for the MM Portfolio site.
- To add another admin: put its folder next to `mm-portfolio/` and copy one `<li>` block in `index.html`.

Cloudflare Pages settings: Framework preset None, Build command empty, Build output directory `/`.
Protect the whole site with Cloudflare Access (see the main instructions, part E).
