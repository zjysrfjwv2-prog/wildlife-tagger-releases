# Requirement: Shareable preview links for artist websites

**Applies to:** the Artist website system.

## The need

We need to send people a link to an artist's website **before it is live on the artist's own domain**. Anyone with the link should be able to open the front end of the site without signing in, so the artist can preview it and show it to other people.

## What it should do

- [ ] Every artist site gets a preview link (e.g. `https://<our-domain>/preview/<artist-slug>-<random-token>`) that works before a custom domain is connected.
- [ ] The link shows the **public front end only**: no dashboard, no editing, no account data.
- [ ] No login needed. The link works for the artist, their friends, and customers.
- [ ] The link is hard to guess (long random token), so only people who were sent it can find it.
- [ ] Preview pages are hidden from search engines (`noindex`) until the site goes live.
- [ ] Ability to turn off or regenerate a link if it gets shared too widely.
- [ ] Optional: show a small "Preview" banner so viewers know the site isn't live yet.
- [ ] Optional: an expiry date on the link.
- [ ] Easy to copy the link from the dashboard and paste it into the emails we send artists.
- [ ] Once the custom domain is live, the preview link either keeps working or redirects to the real domain.

## Related

- Mockups shown on preview sites must follow `artist-mockup-styling.md` (art shown in rooms that suit the artist's style).
