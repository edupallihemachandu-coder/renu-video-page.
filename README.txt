RENU VIDEO QR WEBPAGE — SETUP GUIDE
=====================================

FILES
- index.html : cute pink/hearts video webpage
- video.mp4  : your uploaded video

IMPORTANT
The QR code cannot be finalized until the webpage has a public URL. This ZIP does not contain a fake/placeholder QR code. After publishing, copy the public site URL and use it to create the QR code (or send the URL back to ChatGPT to prepare it).

FREE HOSTING OPTION: GITHUB PAGES
This package includes a ~22 MB video. Netlify Drop documentation recommends deploys under 50 MB and notes individual files over 10 MB may stall, so GitHub Pages is a better fit for this particular file.

1. Sign in or create an account at https://github.com/
2. Create a NEW PUBLIC repository, for example: renu-video-page
3. Upload BOTH index.html and video.mp4 to the repository's top level (root).
   - Use “Add file” → “Upload files”.
   - The video is around 22 MB, so upload it as a single file. Do not use GitHub's web editor for the video.
4. Open repository Settings → Pages.
5. Under “Build and deployment”, choose “Deploy from a branch”.
6. Select branch “main” and folder “/(root)”, then Save.
7. Wait for GitHub Pages to publish. The site URL will look like:
   https://YOUR-USERNAME.github.io/renu-video-page/
8. Open that URL on your phone and test the video and sound.

MAKE YOUR QR CODE
1. Once the public URL works, create a QR code that points to the FULL webpage URL (ending in /).
2. You can send the URL back to ChatGPT and ask for a printable QR code.
3. Test the QR code using a second phone or a camera app before printing.

PLAYBACK NOTES
- Most mobile browsers block autoplay with sound. The page attempts muted autoplay and offers a clear “Turn sound on” button; if autoplay is blocked, tap “Play video”.
- Smooth playback cannot be guaranteed on every device/network. A reliable internet connection and compatible MP4 encoding are required.
- The GitHub repository must remain public for public access to GitHub Pages on the free plan. Anyone with the URL/QR may be able to access the page and video.
- If the uploaded MP4 is encoded with an unsupported codec, convert it to H.264 video + AAC audio in an MP4 container and replace video.mp4.
