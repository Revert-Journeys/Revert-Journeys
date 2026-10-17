# Rename checklist: Revert Journeys

The site text, address and share image now say Revert Journeys and revertjourneys.uk. One thing is still open.

1. **Domain.** Done: `SITE_URL` and the `og:image` line point to `https://revertjourneys.uk`. If you change domain again, edit both (search for `og-image.png` and `SITE_URL`).
2. **Email.** Change `SITE_EMAIL='hubrevert@gmail.com'` only if you move to a new address. Then search the file for `hubrevert@gmail.com` and replace the remaining links (footer, shahada button). After you change it, send one test message on the Ask page and click the FormSubmit activation link in the new inbox.
3. **Instagram.** Done: the handle is now `revertjourneysuk`.

Also replace: the gold door logo is already in `public/favicon.svg` and `public/assets/revert-journeys-logo.svg`. Update the Instagram profile picture with `revert-journeys-profile-1080.png`. Colour is easy to change: edit the three hex values in the gradients.

Old project names in Cloudflare and GitHub are only labels. You can leave them.

**About `wrangler.jsonc`.** The `"name"` line must match the project name shown in Cloudflare (it is `revert-journeys` in this version). Leave it as it is. If you ever rename the project in Cloudflare, rename it here to match, in the same sitting.
