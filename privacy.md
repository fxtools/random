# A small privacy how-to

## Browser

### Download [Chromium](https://chromium.woolyss.com/)
  1. [chose proper version](https://i.imgur.com/edsyU0f.png)
    * ``all-codecs`` (video support)
    * ``widevine`` (digital rights management for Netflix, Amazon, ...)
    * ``no-sync`` (google sync; there is no build with ``all-codecs`` and ``no-sync``)
  2. download it
  3. double-click ``chromium-sync.exe`` to install (there is no indication what so ever. It is just there afterwards.)
  4. start it
  5. add it to taskbar
  6. [right-click and edit ``settings``](https://i.imgur.com/WtWPPsc.png)
  7. [add ``--incognito`` flag to start command](https://i.imgur.com/nnnvGth.png)

### Install [uBlock](https://github.com/gorhill/uBlock#chromium)
  1. [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
  1. [uBlock Origin Extra](https://chrome.google.com/webstore/detail/ublock-origin-extra/pgdnlhfefecpicbbihgmbmffkjpaplco)
  1. check Author for both extensions: Raymond Hill (gorhill)
  1. open extensions view ``chrome://extensions/``
  1. click on ``Details`` of both extensions and allow both in ``incognito mode``

### Fix Chrome settings
  1. open ``chrome://settings/`` go to ``extended`` and disable ``allow login in Chromium``
  1. open ``chrome://settings/content`` and allow normal cookies but disable third-party cookies (and delete everything on close)
  1. open ``chrome://settings/syncSetup`` and [disable sync](https://i.imgur.com/qeriTkR.png)
  2. open ``chrome://settings/passwords`` and disable auto-login
  3. open ``chrome://settings/payments`` and diable auto-payments
  4. open ``chrome://settings/autofill`` and disable auto-fill-in
  5. open ``chrome://settings/searchEngines`` and add [duckduckgo](https://i.imgur.com/DBKhVVB.png) as default search engine
* type ``!g taylor swift`` to search with google
* type ``!b taylor swift`` to search with bing
* type ``!y taylor swift`` to search with yahoo
* or use other [shortcuts](https://duckduckgo.com/bang)

#### Firefox is spying, too! And they have some [NSA guy](https://twitter.com/firefox/status/1027918492643799040) oversee it! ha ha

## Other
* Hosts file: https://github.com/StevenBlack/hosts#list-of-all-hosts-file-variants
* win10-do-not-track howto: https://www.fdossena.com/?p=w10debotnet/index_1809.frag

### Now just close browser, get a new ip by reconnecting your router and you are done.
* [What is my ip?](https://duckduckgo.com/?q=what+is+my+ip&ia=answer)
