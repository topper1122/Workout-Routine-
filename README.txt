HOW TO PUT THIS ONLINE (GitHub Pages)

1. Create a new repo on GitHub (for example: workout-routine).
2. Upload ALL files from this folder except this README: index.html, manifest.json, sw.js and the 3 icon PNGs.
3. Repo Settings > Pages > Source: "Deploy from a branch" > main > / (root) > Save.
4. After about a minute, open https://YOUR-USERNAME.github.io/workout-routine/ on your phone.
5. Install it:
   - Android (Chrome): menu > "Install app"
   - iPhone (Safari): Share > "Add to Home Screen"

Changing exercises: open index.html and edit the PLAN list near the top of the script. If you change files later, change CACHE = 'workout-routine-v1' in sw.js to v2 so phones refresh.
