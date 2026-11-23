# Sarthak & Ranjini · Wedding Invitation

A mobile wedding invitation website, ready to host for free on GitHub Pages.

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The invitation page (all design, text and animation) |
| `assets/photo1.jpg` … `photo5.jpg` | Photos for the Our Story carousel |
| `assets/photo1-blur.jpg` … | Small blurred backdrops for the carousel |
| `assets/hero-bg.jpg` | Blurred background behind the names on the first page |
| `assets/music.mp3` | Background music (plays after the guest taps the book) |
| `assets/preview.jpg` | Picture shown when the link is shared on WhatsApp |
| `assets/icon.png` | Browser tab / home-screen icon |
| `.nojekyll` | Tells GitHub to serve the files as they are |

## Put it online (about 5 minutes, no coding)

1. Sign in at **github.com** (or create a free account).
2. Click **+** (top right) → **New repository**.
   - Name it something short, e.g. `sarthak-ranjini`.
   - Choose **Public** (free GitHub Pages needs a public repository).
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Unzip the download on your computer, open the folder, select **everything inside it**
   (`index.html`, the `assets` folder, `README.md`, `.nojekyll`) and drag it into the GitHub page.
   - `.nojekyll` is a hidden file. On a Mac press **Cmd + Shift + .** in Finder to see it;
     on Windows tick **View → Hidden items**. If it won't upload, the site still works without it.
   - Make sure `index.html` sits at the top level, **not** inside another folder.
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under **Build and deployment**, set
   **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, then **Save**.
7. Wait 1–2 minutes and refresh. Your link appears at the top, e.g.
   `https://your-username.github.io/sarthak-ranjini/`

Open the link on your phone and check it works (tap the book, sound on) before sending it.

## Make the WhatsApp preview picture appear (optional, recommended)

WhatsApp needs the full web address of the preview image.
In `index.html`, find this line near the top:

```html
<meta property="og:image" content="https://YOUR-USERNAME.github.io/YOUR-REPO/assets/preview.jpg">
```

Replace `YOUR-USERNAME` and `YOUR-REPO` with yours, e.g.
`https://ranjini123.github.io/sarthak-ranjini/assets/preview.jpg`.
To edit on GitHub: open `index.html` → pencil icon → change it → **Commit changes**.

WhatsApp remembers previews, so do this **before** you send the link to anyone.

## Changing text later

All event details are near the bottom of `index.html` in the section marked
`CONFIG — edit here` (photo captions, wedding start time, reception time, venues and map links).
Names and the closing message are in the page itself; use your browser's or GitHub's
search (Ctrl/Cmd + F) to find the words you want to change. After you commit a change,
the live site updates within a minute or two.

## Notes

- Fonts load from Google Fonts, so guests need to be online (they will be, to open the link).
- Music only starts after the guest taps the book; phones don't allow sound before a tap.
- The music is the instrumental of a copyrighted film song. Sharing the link privately with
  guests is the usual way; avoid posting it publicly on social media.
