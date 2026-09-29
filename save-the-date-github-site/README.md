# Save-the-Date Website

A mobile-first single-page website for GitHub Pages.

## What it does

- Uses the portrait save-the-date video as the full-screen page.
- Attempts to autoplay immediately on phones.
- Autoplays muted because Safari/Chrome generally block autoplay with sound.
- Shows a **Tap for sound** control that restarts the video with audio after a user gesture.
- Falls back to a large Play button if autoplay is blocked completely.
- Freezes on the final frame and reveals a button linking to:
  https://fillio.so/r/vyB8kbQwUFdZ

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `save-the-date`.
2. Upload `index.html` and the `assets` folder from this project to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will provide an address similar to:
   `https://YOUR-USERNAME.github.io/save-the-date/`

## Optional custom domain

GitHub Pages supports a custom domain if you later buy one. You can configure it under **Settings → Pages → Custom domain**.

## Changing the form button text

In `index.html`, find:

    Open the information form

and replace it with whatever you want, for example `RSVP`, `Svaraðu hér`, or `Send us your details`.
