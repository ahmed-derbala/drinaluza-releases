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

## [1.75.0] - 28 september 2026

### Added
- Added a changelog viewer to the latest release card.
- Added a plus-button chooser to add a file by uploading or pasting a URL.

### Changed
- Renamed IconTextBaseButton to TextIconBaseButton across the app.
- Push notification project ID is now read from config instead of app.json extras.
