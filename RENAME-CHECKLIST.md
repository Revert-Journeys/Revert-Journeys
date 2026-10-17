# Rename checklist: Revert Journeys

The site text now says Revert Journeys and Revert Circles. Three things still point to the old setup. Change them when the new ones exist.

1. **Domain.** In `public/index.html`, near the top of the script, change `SITE_URL='https://reverthub.uk'` to the new domain. Also change the `og:image` line in the `<head>` (search for `og-image.png`) so link previews in WhatsApp use the new domain. Then add the new custom domain in Cloudflare (Workers & Pages, your project, Settings, Domains).
2. **Email.** Change `SITE_EMAIL='hubrevert@gmail.com'` in the same line. Then search the file for `hubrevert@gmail.com` and replace the remaining links (footer, shahada button). After you publish, send one test message on the Ask page and click the FormSubmit activation link in the new inbox.
3. **Instagram.** Done: the handle is now `revertjourneysuk`.

Also replace: the gold door logo is already in `public/favicon.svg` and `public/assets/revert-journeys-logo.svg`. Update the Instagram profile picture with `revert-journeys-profile-1080.png`. Colour is easy to change: edit the three hex values in the gradients.

Old project names in Cloudflare and GitHub are only labels. You can leave them.

**About `wrangler.jsonc`.** The `"name"` line must match the project name shown in Cloudflare (it is `revert-journeys` in this version). Leave it as it is. If you ever rename the project in Cloudflare, rename it here to match, in the same sitting.
