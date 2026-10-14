# ASCII Studio

Browser tool by Woza Labs for turning images into ASCII artwork.

- **Glow**: glyphs tinted by the photo beneath them, with a soft bloom.
- **Defrag**: an object breaks apart into drifting ASCII along one edge.

Exports PNG/JPEG/WebP, copies frames to the clipboard, and renders seamless MP4/WebM loops.

Everything is a single self-contained `index.html` — no build step, no server.
Open it locally or serve it with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

Third-party: [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) (MIT) is inlined for MP4 export.
