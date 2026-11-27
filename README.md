# Lyric Reels

Make 9:16 lyric reels in the browser: paste lyrics, add one or more images and a song, sync the lines by tapping, export a video.

No build step. Open `index.html`, or deploy the folder as a static site.

## Deploy
- GitHub: push this folder to a repo.
- Vercel: import the repo, framework preset "Other", no build command, output directory `.`.

## Use
1. Paste lyrics, one line per screen.
2. Add an image (one is enough) and the song audio.
3. Tap to sync, or spread evenly.
4. Export video (records in real time; keep the tab open).

Export is MP4 where the browser supports it, otherwise WebM.

## Install as an app (PWA)
Deploy over HTTPS (Vercel does this), then open the link on your phone:
- Android Chrome: menu > Install app (or Add to Home screen)
- iPhone Safari: Share > Add to Home Screen

It then opens full screen with its own icon and works offline after the first visit. Fonts need internet the first time.
