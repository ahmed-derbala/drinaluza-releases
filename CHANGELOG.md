## [1.82.1] - 19 october 2026

### Added
- A new Backend Settings card in the settings screen lets you choose how many items each page loads, from 10 to 100.
- The feed, search, sales, notifications and products lists now load as many items per page as you chose.
- The dashboards (businesses, super businesses, business products) follow the same page size.
- The businesses list, the categories list, your own businesses and your purchases now send the page size you chose instead of a fixed one.

### Changed
- The business page now shows a business card on top, then the products of the business with the same product cards you see in the feed.
- You can now share a business page directly from its header.
- Photos in the product gallery can now be added by uploading a file or pasting a link.
- Photos you pick are uploaded only after the product is created, so nothing is lost if the product fails to save.
- The photos of an existing product are now view only: adding and removing them from the product screen is not available for now.
- The product page no longer shows the stock, category, availability and price cards for now.

### Fixed
- Fixed the last page of the feed not showing its cards until you reopen the screen.
- Fixed the number of cards in the feed not matching the total count while scrolling.
- Fixed the feed loading twice in a row when you open it, which wasted data.
- Fixed a business page showing only the first 10 products of a business.

### Removed
- The QR code display is removed from the app.
- The QR code scanner is removed from the feed.

## [1.80.8] - 15 october 2026

### Fixed
- Fixed the focused feed card changing rapidly while scrolling.
- The focused card now follows your mouse on web and stays on the centered card on mobile.

## [1.80.6] - 15 october 2026

### Added
- The feed now loads the next page in advance, so scrolling never waits at the end of the list.

## [1.80.5] - 15 october 2026

### Fixed
- Fixed feed cards stuck on spinner after scrolling away while photos were still downloading.
- Fixed web feed cards losing their photos when not focused.

## [1.80.4] - 15 october 2026

### Added
- Added photo prefetch options in Media Settings: download feed photos in advance on Wi-Fi (on by default) or mobile data (off by default).

### Changed
- Videos now download once and replay instantly, even offline (first play waits for the download).

### Fixed
- Fixed feed photos and videos flickering or showing a spinner when switching between cards.

## [1.80.3] - 15 october 2026

### Added
- Added a YouTube link to the About screen.

### Changed
- Product names in the feed now appear with their category below them.

### Fixed
- Fixed some feed photos appearing blank until their card is focused.

## [1.80.2] - 15 october 2026

### Added
- Photos and videos you have already viewed now open instantly without downloading again.

### Changed
- When creating a product, the main photo is now automatically the first gallery photo and vice versa.
- Update settings and cached data details moved from the Settings screen to the Updates screen.
- The install button is now disabled for installer files older than the installed app.

## [1.80.1] - 13 october 2026

### Added
- Added a Web Settings section with an option to reload the whole page when you press the refresh button (enabled by default, works on every screen of the web version).

### Changed
- The language buttons in the changelog viewer now show flags and moved to the bottom next to the close button.
- The Tunisian Arabic changelog now reads right-to-left.

### Fixed
- Fixed the app failing to build and open on Android.

## [1.80.0] - 12 october 2026

### Added
- Product cards in the feed now have a share button that shares the product link (on the web version it copies the link for you).

### Changed
- Confirmations (reset app, remove account, cancel order) now appear as windows inside the app, and small notices appear as floating messages instead of popups.
- The server info card now lists users as visitors and connected instead of technical names, and is fully translated.
- Sharing an installer file starts right away without the extra advice screen.

### Fixed
- Fixed uneven spacing between the rows of the server info card.
