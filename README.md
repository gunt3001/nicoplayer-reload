# nicoplayer-reload
A tiny javascript to reload Niconico's [nicovideo.jp](http://nicovideo.jp) video player without reloading the whole page.

This is useful when browsing videos on Niconico that are region locked. You'll still need VPN for the initial step, but you can use this script afterwards to stream the video directly.

1. Use VPN to access the video page
2. Wait for the player to load and disconnect the VPN
3. Run [script](script.js)

You will now stream directly without VPN

You can also turn this into a bookmarklet by putting `javascript: ` before the code and set the whole thing as a bookmark.
