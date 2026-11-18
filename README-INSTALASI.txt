PRISM PWA – GitHub deployment

Upload the following files/folders to the ROOT of the existing GitHub repository:
- index.html
- manifest.json
- sw.js
- icons/prism-192.png
- icons/prism-512.png

Keep the paths and folder names unchanged.

After Cloudflare deploys the update:
1. Open the HTTPS PRISM URL in Chrome on Android.
2. Open Chrome menu (⋮) and choose Install app / Add to Home screen.
3. If the browser shows the in-page “Instal PRISM” button, it can also be used.

Notes:
- The service worker caches the app shell and icons after the first successful visit.
- This does NOT make Leaflet/Turf/PapaParse CDN dependencies or online satellite tiles fully offline.
- PWA installation requires HTTPS (Cloudflare workers.dev is HTTPS).
- Existing application logic and GITA polygon data were retained; PWA files are additive.
