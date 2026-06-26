HONEYSTASH SCHEDULER PWA

What changed:
- Added manifest.webmanifest so phones/desktops recognize it as an app.
- Added service-worker.js for offline loading after first visit.
- Added 192px and 512px app icons.
- Added install/offline status banner.
- Renamed the app entry file to index.html.

How to use:
1. Upload this whole folder to a HTTPS host. GitHub Pages, Netlify, Vercel, Firebase Hosting, or your website all work.
2. Open index.html from that hosted URL on iPhone Safari.
3. Tap Share → Add to Home Screen.
4. Open it from the new Honeystash icon.

Important:
- The schedule data is still saved locally in the device browser using localStorage.
- That means each phone/computer has its own saved copy unless you later connect it to Google Sheets, Firebase, Supabase, etc.
- Service workers require HTTPS or localhost. They usually will not work from a plain file:// link.
