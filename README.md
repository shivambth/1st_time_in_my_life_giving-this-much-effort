# Aira — My Favourite Chapter ❤️ (Updated)

## What's improved
- Exactly **50 reasons**, followed by: “So many reasons… I can make unlimited books just to write down all the reasons why I love and appreciate you.”
- A separate floating language switch at the side. Google’s website translation widget translates the visible book to English; Indonesian is the default and no translation paragraphs appear inside pages.
- Pages mix paragraphs, photo moments, stickers and decorative breaks.
- All 50 exact photo filenames supplied are wired into the album (three photos per album page).
- Floating music player is included. Add your MP3 as `assets/music/our-song.mp3`.

## Add your 50 photos
1. Open `assets` → `photos`.
2. Upload all 50 image files listed in `PHOTO_FILENAMES.txt`.
3. Keep every filename exactly the same, including hyphens and `.jpeg`.

**Important:** You supplied the filenames, not the actual image files. The website is wired to those names, but the images themselves must be uploaded into `assets/photos/`.

## Add your song
Upload an MP3 into `assets/music/` and name it `our-song.mp3`. Then tap “Play our song”.

## Publish with GitHub Pages
Upload `index.html`, `style.css`, `script.js`, and the complete `assets` folder to your repository. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

## Notes
- The English switch requires an internet connection and Google’s translation widget. Indonesian is the default.
- Music does not autoplay; the visitor must tap Play.
- Aira's saved message stays in that browser/device only.

## Final repair pass
- Fixed a JavaScript scope/return bug that prevented the language and music buttons from receiving their click handlers.
- Corrected the “100 reasons” footer label to “50 reasons”.
- Hid the Google Translate overlay/banner UI and kept the translation control as a compact side button.
- Improved iPhone viewport sizing, safe-area spacing, and photo fitting so pages are less likely to crop or overflow.
- Added a retry action for mini-games.
\n**Photo reminder:** only the 50 filenames were supplied in chat; the image files themselves still need to be uploaded into `assets/photos/`.\n