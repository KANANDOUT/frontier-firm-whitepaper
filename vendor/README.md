# vendor/

Place **`three.min.js`** (Three.js r149) in this folder.

Download it from:
https://cdn.jsdelivr.net/npm/three@0.149.0/build/three.min.js
(right-click → "Save as…" → `three.min.js`)

`index.html` loads `vendor/three.min.js` first. If the file is missing, it falls
back to the public CDN so the page still works. License: MIT — see
`../THIRD_PARTY_NOTICES.md`.
