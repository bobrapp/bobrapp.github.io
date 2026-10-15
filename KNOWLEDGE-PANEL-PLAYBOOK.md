# Bob Rapp — DIY Google Knowledge Panel Playbook

What the LinkedIn pitch sells for a "one-time investment" is mostly free work you control. Google does not sell or guarantee knowledge panels; it builds them from consistent, corroborated facts about a person. The steps below put those facts in place.

## 1. Publish the entity home (done, pending your approval to go live)

`index.html` in this folder is your official "entity home" page. It contains:

- A schema.org `Person` + `ProfilePage` JSON-LD block (name, job title, employers, education, credential, expertise, photo).
- `sameAs` links tying the page to LinkedIn, GitHub, YouTube, and the AiGovOps Foundation.
- `rel="me"` links, canonical URL, Open Graph tags, `robots.txt`, and `sitemap.xml`.

Recommended home: `https://bobrapp.github.io/` (free, permanent, you own it). Optional: point `bobrapp.cloud` at it later with a CNAME file.

## 2. Make every profile point back (about 20 minutes)

Google trusts facts that agree across sources. Use the same one-line bio everywhere:

> Bob Rapp is a Principal AI Architect at the General Motors AI Center and co-founder of the AiGovOps Foundation.

- LinkedIn → Contact info → Website: add `https://bobrapp.github.io/` (type: Personal).
- GitHub → Edit profile → Website: `https://bobrapp.github.io/`. Consider updating the bio to the line above.
- YouTube → Customize channel → Basic info → Links: add the site; paste the bio into the description.
- AiGovOps Foundation site → team/founders page: link "Bob Rapp" to `https://bobrapp.github.io/`.
- TDWI / AI House speaker pages: ask organizers to link your name to the site.

## 3. Verify in Google Search Console (10 minutes)

1. Go to https://search.google.com/search-console and add a URL-prefix property for `https://bobrapp.github.io/`.
2. Choose the HTML-tag method; send me the tag and I'll add it to the page.
3. Submit `https://bobrapp.github.io/sitemap.xml` and request indexing of the homepage.
4. Check the page with https://search.google.com/test/rich-results to confirm the Person data is read.

## 4. Create a Wikidata item (30 minutes, highest-leverage step)

Wikidata is a primary source for Google's Knowledge Graph. Create an item at https://www.wikidata.org/wiki/Special:NewItem with:

- Label: Bob Rapp · Description: American AI architect and AI governance practitioner
- instance of (P31): human · sex or gender (P21) · country of citizenship (P27): United States
- occupation (P106): software architect · employer (P108): General Motors
- founded by (P112) on an AiGovOps Foundation item (create it too, with its website)
- educated at (P69): University of Washington; Northwest Nazarene University
- official website (P856): `https://bobrapp.github.io/` · LinkedIn ID (P6634): bobrapp · GitHub username (P2037): bobrapp · YouTube channel ID (P2397)
- Add a reference URL to every statement (TDWI agenda, Foundation site, LinkedIn). Unsourced items for living people get deleted.

Do not write your own Wikipedia article; that is a conflict of interest and tends to get removed.

## 5. Earn independent mentions (ongoing)

Third-party pages are what convert a profile into a panel: conference speaker pages, podcast guest pages, press quotes, published articles with an author bio, and Google Scholar/Google Patents entries. Each should use the same name, title, and link.

## 6. Claim the panel once it appears

When searching "Bob Rapp" shows a panel on the right, click "Claim this knowledge panel," sign in with Google, and verify through your linked YouTube or Search Console account. Then you can suggest edits directly. Timing varies — often weeks to months.

## About the outreach message

The message follows a common cold-outreach pattern (unsolicited "I Googled you" hook, celebrity example, "done-for-you in 30 days," one-time fee). Nobody can guarantee a knowledge panel, and paid services generally do the steps above. No need to reply.
