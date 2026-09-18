# 5-Month Anniversary Website ❤️

## IMPORTANT: How the photo appears automatically
This version is designed so that **her photo is already part of the website**.

Before you deploy:
1. Put the couple photo in `assets/us.jpg`.
2. Put the song in `assets/our-song.mp3`.
3. Keep the `assets` folder beside `index.html`.
4. Upload the entire folder to GitHub Pages, Netlify, or another static host.

When she opens your public link, the browser loads `assets/us.jpg` automatically. She does NOT need to upload or select the photo.

If your photo has another filename, change this line near the top of `index.html`:
`const PHOTO_FILE = "assets/us.jpg";`

For the song, change:
`const SONG_FILE = "assets/our-song.mp3";`

## Music
The opening button starts the song after she taps it. This is intentional because phone browsers often block autoplay with sound before a user interaction.

## Customize
Replace `[HER NAME]` and `[YOUR NAME]` and edit any message directly in `index.html`.

## Deploy
### GitHub Pages
Upload `index.html` and the `assets` folder to a repository, then enable Pages from the main branch.

### Netlify
Upload/drag the complete website folder to Netlify. Do not upload only `index.html`; the `assets` folder must be included.
