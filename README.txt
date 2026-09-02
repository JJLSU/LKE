LAST KIDS ON EARTH - v140 EXTERNALIZED BUILD

This build separates the game code from the embedded images and music.

TO PLAY
1. Keep index.html and the assets folder together.
2. Double-click index.html.

If your browser blocks local media, use the included START_LOCAL_SERVER.bat on Windows, then open:
http://localhost:8000/

WHY THIS BUILD IS DIFFERENT
- The HTML is now small instead of ~160 MB.
- Images and music live in the assets folder.
- Duplicate embedded assets are stored only once.
- This structure is much easier to edit, transfer, and host on GitHub Pages.

Do not move index.html away from the assets folder unless you also update the relative asset paths.
