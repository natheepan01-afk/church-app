CHURCH SYSTEM PWA v1.2 - iPhone STATUS BAR + CACHE FIX

This release:
- stops caching index.html
- removes old service-worker caches
- reserves 48px at the top only when opened as an installed iPhone PWA
- leaves the Apps Script Church System untouched

Upload ALL files to the root of the same GitHub repository and Commit.

IMPORTANT after GitHub Pages deploys:
1. Delete the existing Church System icon from the iPhone Home Screen.
2. In Safari open:
   https://natheepan01-afk.github.io/church-app/?v=12
3. Confirm the page works.
4. Share > Add to Home Screen again.

This one-time reinstall is required because the old installed PWA may still be controlled by the old cache.
