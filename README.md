# WUS Website - fixed version (no vertical menu)

If you still see a vertical menu, it is from:
- an older cached HTML/CSS, or
- a leftover <div id="mobilemenu"> in your deployment.

This package:
- removes the mobile menu HTML entirely
- force-hides any element matching .mobilemenu / #mobilemenu via CSS
- adds cache-busting query params (?v=2) to CSS/JS links

## Local preview
python3 -m http.server 8000
Open http://localhost:8000
Hard refresh: Cmd+Shift+R (Mac) / Ctrl+Shift+R (Windows)

# Website for public access
https://mark1500woo.github.io/wus-research/
