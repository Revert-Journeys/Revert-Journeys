# How to edit the Revert Journeys site

## Change some wording (2 minutes)
1. Go to the repo on github.com and open the `public` folder, then click `index.html`.
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

## The website forms (Ask, Share your story, Tell us how you would like to help)
- They send straight to hubrevert@gmail.com through a free service called FormSubmit. No email app opens for the visitor.
- First time only: after the site update goes live, fill in and send one test message on the Ask page. FormSubmit will email hubrevert@gmail.com an activation link. Click it once. After that every form works.
- Check the Gmail spam folder if the activation email does not arrive.
- If a form ever fails, the visitor sees a link to email you instead, so nothing is lost.
- Before sharing real stories widely, add a short privacy note (who sees stories, how long you keep them).

## Save as PDF buttons
The Dua and Glossary pages have a "Save as PDF" button. It opens the browser's print window. Choose "Save as PDF" as the destination. The PDF always matches whatever is on the site, so you never need to update a separate file.
