# Revert Journeys website

Support, learning and community for new and returning Muslims. Starting in Manchester, for the UK. In partnership with Al Furqan Islamic Centre.

- `public/index.html` is the whole website (one file). This is the file you edit.
- `public/favicon.svg` is the browser tab icon.
- `public/assets/` holds the logo.
- `wrangler.jsonc` tells Cloudflare which folder to publish. Leave it alone.
- `EDITING-GUIDE.md` shows how to change wording. `RENAME-CHECKLIST.md` lists what to change when the new domain is ready.

Contact: hubrevert@gmail.com

Any change committed here goes live on Cloudflare within about a minute.

## If a host says "Page not found"
The website is the `public` folder. The host must publish **that folder** so `index.html` sits at the top of the site.
- Netlify: `netlify.toml` already says `publish = "public"`. If you drag and drop instead, drag the **public** folder itself (open it first so you see `index.html`).
- Cloudflare: `wrangler.jsonc` already points at `./public`. Its `"name"` must equal the project name in Cloudflare.
- GitHub: `public/` must be at the top of the repository, not inside another folder.
