# KF Commercial Services

Portfolio and contact page for **KF Commercial Services LLC**, Gainesville, Florida.
Window washing, websites and HTML overlays, computer help, and original music.

## What's here

| File | What it is |
| --- | --- |
| `index.html` | The whole site: one self-contained page (HTML, CSS and a little JavaScript) |
| `logo.jpg` | Logo used in the page header |
| `logo-full.png` | Full-size logo (black background, blue K, orange F) |
| `favicon.ico`, `favicon-32.png`, `favicon-192.png`, `apple-touch-icon.png` | Browser tab and phone home-screen icons |
| `KF-Commercial-Services.vcf` | Contact card people can open to save KF to their contacts |
| `ads.txt` | Google AdSense publisher declaration |

## Brand colors

- Black `#000000` (background)
- Blue `#0C0B82` (menu bar, borders, fills)
- Orange `#FC4A04` (headings, links, buttons)

## Features

- Sticky menu that scrolls to each section
- Web and code portfolio linking to the live projects
- Music section linking to each release on Ditto
- Save contact button and a QR code that adds KF to a phone's contacts
- Google AdSense script in the page `<head>`

## Running and publishing

There is no build step. Open `index.html` in a browser to preview it.

To publish with GitHub Pages: repo **Settings -> Pages -> Deploy from a branch -> `main` / root**.
The site then appears at `https://werewolf3788.github.io/KF-Commercial-Services/`.
A custom domain can be added on the same screen.

## Things to keep up to date

- **Window washing:** add real before-and-after photos and a price line once you have finished jobs.
- **Contact card:** if the email or name changes, update it in three places: the page's contact section, the script near the bottom of `index.html`, and `KF-Commercial-Services.vcf`. The QR code image in the contact section also needs regenerating.
- **Music:** new releases go in the Music section as another card linking to the Ditto page.

## AdSense

The AdSense script (`ca-pub-2509348249117288`) is in the `<head>` of `index.html`, and `ads.txt` sits at the site root.
AdSense approves sites it can verify, so add this site's address in the AdSense dashboard once it is live.
A privacy policy page and a custom domain you own both help with approval.
