# Mass Effect Portfolio v7

This version adds a stronger mobile layout and packages the required assets locally.

## What changed

- Mobile bottom dock navigation for section switching
- Phone-friendly top bar and spacing
- Horizontal swipe rail for the right-side context panels on smaller screens
- Smaller bundled audio file for faster loading
- `.nojekyll` included for GitHub Pages

## Local preview

Open `index.html` directly, or serve the folder locally:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Recommended deployment

The simplest deployment path for this project is GitHub Pages because this is a static HTML/CSS/JS site.

1. Create a GitHub repository for the site.
2. Upload the contents of this folder, keeping `index.html` in the repo root.
3. In GitHub, open **Settings → Pages**.
4. Set **Source** to **Deploy from a branch**.
5. Choose `main` and `/ (root)`.
6. Wait for GitHub Pages to publish the site.

If you want a custom domain later, connect it in your Pages settings after the first successful deploy.

## Important note about soundtrack

The packaged MP3 here is a short preview loop made from the reference audio you uploaded for local testing. Before publishing publicly, replace it with audio you have the rights to distribute, or remove soundtrack playback entirely.

To swap the audio file, replace:

`assets/audio/n7-network-loop.mp3`

and keep the same filename.

## Files that matter most

- `index.html` — everything lives here
- `assets/resume/Hayden_Lane_Resume_Chevron.pdf`
- `assets/audio/n7-network-loop.mp3`
