WESS HEROES COLORING STUDIO — PROTOTYPE
========================================

FILES
- index.html: the app (gallery, brush, eraser, undo, reset, save PNG)
- manifest.webmanifest: installable web-app metadata
- sw.js: basic offline caching

IMPORTANT
The three starter characters are simple placeholder robot line art, not the final established WESS character designs. Replace/update the SVG artwork with approved WESS pages before public launch.
The Premium button currently points to https://payhip.com/ as a placeholder. Change its href in index.html to your own Payhip store or product URL.

HOW TO TEST ON ANDROID
1. Extract the ZIP on your phone or computer.
2. Open index.html in a browser if your file manager allows it. Some features, especially install/offline support, require hosting over HTTPS.
3. Test drawing, erasing, undo, reset and Save PNG.

FREE PUBLISHING WITH GITHUB PAGES (ANDROID)
1. Sign in or create a GitHub account at https://github.com/
2. In your browser, open GitHub and create a new PUBLIC repository named wess-coloring-app.
3. In the repository choose Add file > Upload files.
4. Upload index.html, manifest.webmanifest, and sw.js from this ZIP (upload the files, not the ZIP).
5. Commit the upload.
6. Open repository Settings > Pages.
7. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
8. Wait for the published URL shown on the Pages screen. It should resemble https://YOUR-USERNAME.github.io/wess-coloring-app/
9. Open that URL on your phone and test it. In Chrome, use menu ⋮ > Add to Home screen (wording can vary).

PAYHIP LINK
Edit index.html, find https://payhip.com/, and replace it with your real product/store URL. Upload the updated index.html to GitHub again.

LIMITATIONS OF THIS FIRST PROTOTYPE
- Brush coloring draws over the page; it does not flood-fill enclosed regions.
- Artwork is placeholder line art; it does not yet use the user's uploaded PDF or official character references.
- No accounts, cloud sync, in-app checkout, ads, analytics, or payment processing are included.
- Save PNG exports the visible coloring canvas.

CHILD SAFETY / PRIVACY
For a child-directed release, avoid collecting personal data, add an appropriate privacy notice, and review applicable platform and child privacy rules before adding analytics or ads.
