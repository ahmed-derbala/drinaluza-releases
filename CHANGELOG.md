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

## [1.79.4] - 12 october 2026

### Added
- When requesting a business account, you now choose your own short link (shown as drinaluza.com/b/your-link). Only english letters, numbers and "-" are allowed.
- Added a Purchases section in Settings with a purchase confirmation switch, right after Media Settings.

### Changed
- In the business request form, the link field now comes first and the business name is optional.
- The purchase confirmation switch moved from your Profile to Settings and is now saved on your device.
- The server info card now shows the environment (for example production) as a small badge in the top right, with the app name and version as a regular row.

### Fixed
- Fixed missing gaps between the cards in the business request form.
- Removed the example texts inside the contact fields and the business link field.
- Business request, name, contact, preferred contact and purchases settings now appear in your language (english, tunisian latin, arabic).

## [1.79.3] - 11 october 2026

### Enhanced
- Prices now display cleanly without extra zeros (5 instead of 5.00) everywhere: product cards, cart and checkout.
- The quantity stepper now shows the unit next to the amount (for example 1 kg).
- Product photos now fill the whole feed card, and photo thumbnails are always visible.
- Feed cards show the product category below the product name.

### Fixed
- Fixed the quantity stepper starting from a wrong tiny amount when the minimum is fractional (for example 0.01 instead of 0.1).
- Fixed the total price being wrong as a result of the wrong starting quantity.
- Fixed a black strip appearing at the bottom of feed cards on the web version.

### Added
- The price input now accepts up to 6 digits before the dot and 3 digits after it.

## [1.79.0] - 9 october 2026

### Added
- The app now downloads updates automatically in the background on wifi or mobile data (depending on your settings) and opens installation when finished.
- When automatic download is off, the app opens the updates screen when a new version is available.

### Fixed
- Fixed automatic update download not starting on app launch.
