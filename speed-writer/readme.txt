# Speed Writer Change Log

[Chrome Extension](https://chrome.google.com/webstore/detail/speed-writer/pckbepeadbhaafeeagcgfiepngbioalg?utm_source=chrome-ntp-icon)

version 1.1.1
Redesign

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
