# Send Love to da Fooj 💖

A quiet little walk through the mist to a shrine where a priest cat is collecting
good vibes for Fooj's surgery day. Every vibe makes the cat bow, sends hearts into
the sky, and plants a flower in the garden around the shrine — the garden is saved
on the visitor's device, so it keeps filling in as Nandini returns.

Everything lives in a single `index.html` — no build step, no dependencies to
install (Three.js loads from a CDN at runtime).

## Controls

- **Desktop:** W (or ↑) to walk · A / D to turn · drag to look · E to send vibes at the shrine
- **Phone:** hold to walk · drag to look · tap the button at the shrine

## Hosting it

Any static host works. Two easy options:

**Netlify Drop (fastest):** go to https://app.netlify.com/drop and drag this folder in.
You'll get a shareable URL in seconds.

**GitHub Pages:** create a repo, add `index.html`, then Settings → Pages → deploy from
the main branch. The site appears at `https://<you>.github.io/<repo>/`.

Then just text the link to Nandini. 🐾

## Notes

- The vibe counter and the planted garden are stored in the visitor's browser
  (localStorage), so each device grows its own garden for Fooj.
- Blessing messages rotate with each vibe — edit the `MESSAGES` array in `index.html`.
- The dedication line ("with love, for nandini & fooj") is plain HTML near the top of the file.
