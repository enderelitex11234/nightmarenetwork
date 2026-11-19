# NIGHTMARE NETWORK — Multipage Inline Website

Every page has its CSS and JavaScript embedded directly inside its HTML file. No separate CSS or JS files are required.

## Pages
- index.html — Home
- about.html — About
- game-modes.html — Game modes
- rules.html — Rules
- staff.html — Staff
- status.html — Server info
- join.html — Join
- 404.html — Not found

## Configure server details
On each HTML page, find `window.NIGHTMARE_CONFIG` near the bottom and update:
- `serverAddress`
- `discordInvite`
- `minecraftVersion`
- `edition`

Keep these settings identical on all pages.

## Test on Android
Extract the ZIP, open the folder in Acode, then open `index.html` using Preview. If you use a local server app, serve this folder and visit its localhost URL.

## GitHub Pages
Upload all HTML files to the repository root. Set GitHub Pages to deploy from your main branch and root folder.

Note: This is a static website. Live player count, server status checks, accounts, and admin features are not connected.
