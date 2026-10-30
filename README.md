# Ear Training Tools

Static browser-based practice tools (no build step). Open `index.html` or publish the folder as-is.

Published structure:

- `/` main index
- `/intervals/` interval trainer
- `/chords/` chord trainer
- `/progressions/` chord progression trainer
- `/melodic/` melodic dictation trainer
- `/minor-scales/` minor scale trainer
- `/related-keys/` related key trainer
- `/modes/` mode trainer (10 phrase variants per mode)
- `/key-signatures/` key signature trainer
- `/rhythm/` rhythm dictation trainer

Shared files: `style.css` and `nav.css` (index layout and the back button / topbar), `lang.js` (JA / EN / FR toggle), `assets/`.
Each trainer folder has its own `index.html`, `app.js` and `style.css`.

## Notes

Some functions use external CDN libraries:

- Tone.js
- abcjs
- jsPDF

Real piano sounds, notation display and PDF export require an internet connection.

Interval and chord trainers use treble-range notes up to A5 where possible.
