# How to edit the Revert Hub site

## Change some wording (2 minutes)
1. Go to the repo on github.com and click `index.html`.
2. Click the pencil icon (Edit this file).
3. Press Ctrl+F (Cmd+F on Mac) and search for the sentence you want to change.
4. Change only the words. Do not touch anything inside < > or the quote marks.
5. Click Commit changes. Write a short note like "Fix class time". Choose "Commit directly to main".
6. Wait about a minute, then refresh the live site and check it.

## Replace a "coming soon" link
Find the text, e.g. `Guide coming soon`. The line looks like:
`<div class="links"><span>Guide coming soon</span></div>`
Replace the `<span>...</span>` with a link:
`<a href="https://the-link-here" target="_blank" rel="noopener">Read the guide</a>`

## Add the Instagram link (footer)
Search for `Social channels coming soon` and replace it with:
`<a href="https://instagram.com/YOUR_HANDLE" target="_blank" rel="noopener">Instagram</a>`

## If you break something
Open the file on GitHub, click History, find the last good version, and click the three dots then "Revert". Cloudflare republishes the old version.

## Rules for the team
- Wording and links only here. For new sections or design changes, ask Claude and paste in the latest index.html first, so earlier edits are not lost.
- Religious content (duas, guides, rulings) should be checked by a scholar before it goes live.
- Never put passwords, personal phone numbers or anyone's story without written consent into this repo. It may be public.
