Camp Mat2B Journal - how to put it online

1. Upload EVERYTHING in this folder (index.html, the img folder, the media folder)
   into one folder on your host, e.g. public_html/matt/
   (cPanel: File Manager > upload the zip > right-click > Extract.)
   Or drag this whole folder onto https://app.netlify.com/drop for a free https link.
2. The site must be served over https:// so the Spotify player and video work everywhere.
3. Open the link on your phone and check: Spotify player shows on the Soundtrack page,
   the map loads on the Europe page, the video plays.

Nothing else is needed: no database, no build step, no plugins.
The Spotify player, the Europe map data (jsdelivr) and fonts (Google Fonts) load from the internet.
