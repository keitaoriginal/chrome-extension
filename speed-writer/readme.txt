memo
manifest.js
open extension when open a new tab
## no need background.js
  "chrome_url_overrides": {
    "newtab": "index.html"
  },

## need backgroun.js
  "background": {
    "scripts": ["background.js"],
    "persistent": false
  }
