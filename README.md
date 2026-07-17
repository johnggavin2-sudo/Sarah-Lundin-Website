# Sarah Lundin — Author Website

A 5-page site: Home, Books, About, News, Contact. Plain HTML/CSS, no build
tools, no database — every page is a file you (or I) can open and edit
directly.

## Getting it online (free, ~10 minutes)

You said you haven't bought a domain yet, so here's the simplest path:

1. **Get the domain.** Buy `sarahlundin.com` from a registrar like
   Namecheap or Google Domains ($10–15/year).
2. **Host the site for free on Netlify:**
   - Go to netlify.com and create a free account.
   - Drag this whole folder onto the Netlify dashboard ("Deploy manually" /
     drag-and-drop upload). That's it — it's live on a netlify.app address
     within seconds.
   - In Netlify's site settings, add your custom domain
     (`sarahlundin.com`) and follow the DNS instructions it gives you.
     Netlify also provides free HTTPS automatically.
3. **The contact and newsletter forms** are already wired for **Netlify
   Forms** (that's what `data-netlify="true"` does) — once the site is
   deployed on Netlify, form submissions show up automatically in your
   Netlify dashboard under Forms, no extra setup needed. If you'd rather
   route newsletter signups into an actual mailing list (e.g. MailerLite,
   which you're already connected to), let me know and I can wire that up
   too.

## How to update the site yourself

Every page is a plain HTML file with comments marking what to edit:

- **Add a book:** open `books.html`, copy one `.book-card` block, paste it,
  edit the title/blurb.
- **Add a news post:** open `news.html`, copy one `.post-item` block, paste
  it above the others, edit the date/title/text.
- **Edit your bio or photo:** open `about.html`.
- **Colors and fonts:** all defined once at the top of `styles.css` — change
  a value there and it updates everywhere.

You don't need any special software — Notepad or TextEdit works, though a
free editor like VS Code makes it easier to see what you're doing.

## The easiest path

Anytime you want a change and don't want to edit the code yourself, just
come back to this chat (or paste these files into a new one) and tell me
what to change — I'll edit the files directly and hand back the updated
site.

## Files in this folder

- `index.html` — Home
- `books.html` — Full series listing
- `about.html` — About the author
- `news.html` — Blog/news posts
- `contact.html` — Contact form + newsletter signup
- `styles.css` — All design/styling (shared by every page)
