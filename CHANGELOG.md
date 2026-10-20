## [1.85.0] - 20 october 2026

### New

- Tunisian Arabic is now the default app and content language.
- A language card in the settings screen lets you change the app language and the content language; your choice is kept on this device.
- On Android and on the web version, the updates screen now shows a storage card: the size of the cache and documents folders with their clear buttons on Android, and the number of storage and secure-storage keys on both.
- A new Backend Settings card in the settings screen lets you choose how many items each page loads.
- The feed, search, sales, notifications and products lists now load as many items per page as you chose.
- The feed, products, notifications and sales lists now keep all loaded pages available offline.
- Every list now can show its already loaded pages instantly, even after closing the screen, and refreshes them from the backend when it is reachable.
- Lists no longer ask the backend for anything while it is offline; cached pages are shown instead.
- The dashboards (businesses, super businesses, business products) follow the same page size.
- The businesses list, the categories list, your own businesses and your purchases now send the page size you chose instead of a fixed one.
- The business page now shows a business card on top, then the products of the business with the same product cards you see in the feed.
- You can now share a business page directly from its header.
- Photos in the product gallery can now be added by uploading a file or pasting a link.
- Photos you pick are uploaded only after the product is created, so nothing is lost if the product fails to save.
- The photos of an existing product are now view only: adding and removing them from the product screen is not available for now.
- The product page no longer shows the stock, category, availability and price cards for now.

### Fixed

- The app language now applies instantly across the whole app when you switch it in the settings screen, without reloading screens or lists.
- Fixed the business page's product strip stopping after the first page when scrolling sideways.
- Fixed the last page of the feed not showing its cards until you reopen the screen.
- Fixed the number of cards in the feed not matching the total count while scrolling.
- Fixed the feed loading twice in a row when you open it, which wasted data.
- Fixed a business page showing only the first 10 products of a business.

### Deprecated

- The app now stores less account data on your device (one snapshot instead of several copies of the same details).
- Temporary download progress is no longer saved on your device.
- Language and currency are no longer part of your account: languages are saved on this device and prices are shown in Tunisian dinar.
- The language picker on the sign-in screen was removed — change languages from the new card in the settings screen.
- The Reset App card is removed from the settings screen.
- The QR code scanner is removed from the feed.

## [1.80.0] - 15 october 2026

### New

- The feed now loads the next page in advance, so scrolling never waits at the end of the list.
- Added photo prefetch options in Media Settings: download feed photos in advance on Wi-Fi (on by default) or mobile data (off by default).
- Videos now download once and replay instantly, even offline (first play waits for the download).
- Photos and videos you have already viewed now open instantly without downloading again.
- Added a YouTube link to the About screen.
- Product names in the feed now appear with their category below them.
- When creating a product, the main photo is now automatically the first gallery photo and vice versa.
- Update settings and cached data details moved from the Settings screen to the Updates screen.
- The install button is now disabled for installer files older than the installed app.
- Added a Web Settings section with an option to reload the whole page when you press the refresh button (enabled by default, works on every screen of the web version).
- The language buttons in the changelog viewer now show flags and moved to the bottom next to the close button.
- The Tunisian Arabic changelog now reads right-to-left.

### Fixed

- The focused feed card no longer changes rapidly while scrolling: it follows your mouse on web and stays on the centered card on mobile.
- Fixed feed cards stuck on spinner after scrolling away while photos were still downloading.
- Fixed web feed cards losing their photos when not focused.
- Fixed feed photos and videos flickering or showing a spinner when switching between cards.
- Fixed some feed photos appearing blank until their card is focused.
- Fixed the app failing to build and open on Android.
