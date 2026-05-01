# Beer Ticker Public Frontend

This folder is the GitHub Pages version of the public beer list.

Setup:

1. Deploy the Apps Script web app.
2. Copy the web app URL.
3. In `index.html`, replace:

   `PASTE_GAS_WEB_APP_URL_HERE?view=public-api`

   with:

   `YOUR_GAS_WEB_APP_URL?view=public-api`

4. Commit this folder to a GitHub repo and enable GitHub Pages.

The page reads public data from GAS through the `public-api` JSONP endpoint.
Service, Büro/Brauerei, and admin stay in GAS for now.
