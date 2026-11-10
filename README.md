# tiffany's hub doorway

A small page that gives Tiffany's hub its own home screen icon and name ("tiffany's hub"). A claude.ai link always saves to an iPhone home screen with the Claude icon, so this page carries the icon and sends a tap on to the real hub.

- index.html: the page Tiffany opens once to add it to her home screen. It swaps its address to go.html, so the home screen saves go.html.
- go.html: opens the hub straight away; the button is a fallback.
- apple-touch-icon.png, icon-192.png, icon-512.png: the Content Engine symbol in moss on stone, rendered from icon.svg.
- manifest.json: the name and icons for Android and other browsers.

Built for Lee and McCabe (Capiral and Lee LLC). If the hub's link changes, change it in index.html and go.html.
