# bare

> a blank page to type in. nothing else.

**bare** is the simplest writing space on the internet. no buttons, no toolbars, no signups, no menus, no distractions. open the page and start typing. that's it.

your text autosaves locally in your browser, so closing the tab won't lose a thing.

## why

most writing apps are bloated. toolbars, sidebars, formatting menus, AI assistants, "premium" popups, sync logins. **bare** removes all of that. one screen. one cursor. you and your words.

## features (yes, even these are minimal)

- full screen writing canvas
- autosaves to localStorage on every keystroke
- restores your text when you reopen
- warns before accidental tab close
- tab inserts two spaces, because indentation matters sometimes
- no tracking, no ads, no analytics, no cookies
- works offline once loaded
- one file, no build step, no dependencies

## use cases

- scratchpad for random thoughts
- journaling without judgment
- drafting before pasting into something serious
- clearing your head on a rough day
- writing letters you'll never send
- the world's most overbuilt to-do list

## running it

it's one HTML file. just open `index.html` in any browser. or host it anywhere static (GitHub Pages, Netlify, Vercel, Cloudflare Pages, a thumb drive).

## deploying on GitHub Pages

1. create a new repo called `bare`
2. push these files
3. Settings > Pages > Source: `main` branch, `/ (root)` > Save
4. wait a minute, visit `https://shehan-fdo.github.io/bare/`

## SEO

this site ships with the full SEO kit:
- meta tags (title, description, keywords, robots, theme-color)
- Open Graph + Twitter Card social previews
- JSON-LD `WebApplication` structured data
- `robots.txt` and `sitemap.xml`
- an OG image for link sharing

remember to replace `YOUR-USERNAME` with your actual GitHub username in `index.html`, `robots.txt`, and `sitemap.xml` after cloning, then commit and push.

## tech

- vanilla HTML, CSS, JavaScript
- no frameworks, no build tools, no npm
- single file, ~3KB minified
- works in every modern browser

## license

MIT. fork it, host it, ship it.
