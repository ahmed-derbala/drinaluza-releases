## [1.79.0] - 9 october 2026

### Added
- Added background auto-update on Android startup gated by connection type: downloads in background and launches installation on finish when auto-update on wifi (default on) or mobile data (default off) is enabled, without navigating.
- Added navigation to the updates screen on startup when an update is available to download but auto-update is disabled for the current connection.
- Added automatic installer launch on startup when an update is already downloaded and ready to install.
- Added background resume of paused update downloads on startup when auto-update allows it, including when the remote check fails.

### Changed
- Replaced @react-native-community/netinfo with expo-network for reading the connection type.
- downloadUpdate and resumeDownload now accept an explicit release and a silent option so background flows do not depend on state closures or show storage alerts.

### Fixed
- Fixed startup auto-update never downloading because downloadUpdate read a stale latestRelease right after checkForUpdates.
- Removed the stale users route entry that caused a no-route warning in the root layout.

## [1.75.0] - 28 september 2026

### Added
- Added changelog viewer to the latest release card (IconBaseButton opening a BaseModal with markdown release notes and a cancel button).
- Added plus-button chooser in MediaCard to add a file by uploading or pasting a URL.

### Changed
- Renamed IconTextBaseButton to TextIconBaseButton across the app.
- Push notification project ID is now read from config instead of app.json extras.
- Piped the GitHub release body through the update check as the changelog source.

## [1.74.1] - 28 september 2026

### Added
- Added preset picker modal (searchable bottom sheet) for product creation.
- Added MediaCard to manage product thumbnail and gallery (upload a file or paste a URL, copy URL, remove, fullscreen preview).

### Changed
- Renamed default product to preset across the app (types, API endpoints, UI labels) to match the backend.
- Unified the thumbnail and gallery blocks in MediaCard with the same tile UI; thumbnail is always one file, gallery holds many.
- Moved MediaCard to the shared core cards folder.
- Pasted file URLs are no longer assigned or sent with a client-generated `_id`.
- Thumbnail preview in MediaCard is now compact instead of full-width.

### Fixed
- Fixed the preset picker list scrolling inside the bottom sheet.

## [1.70.2] - 22 september 2026

### Changed
- Pointed the release scripts (APK publishing and changelog sync) back to the drinaluza-releases repository.

### Removed
- Removed the ESLint setup (config file, dev dependencies, and global install reference).

## [1.70.1] - 22 september 2026

### Changed
- Switched the app config to the production flavor (production name, icon, Android package, link scheme, and NODE_ENV).

## [1.69.0] - 22 september 2026

### Added
- Added docs/.env.example template documenting the required public environment variables.

### Changed
- Pointed the release scripts (APK publishing and changelog sync) to the drinaluza-releases repository.
- Allowed docs/.env.example through .gitignore and .easignore while keeping real .env files ignored.

## [1.65.0] - 21 september 2026

### Enhanced
- Improved the product feed card layout with better spacing and visual hierarchy.
- Updated Expo SDK packages (expo, expo-router, expo-updates, expo-notifications, expo-location, expo-sharing, expo-build-properties) for stability and compatibility.
- Improved Android release build reliability by enabling the new architecture with SDK auto-download and limiting parallel build jobs to prevent out-of-memory errors.

### Fixed
- Fixed the product feed card layout on mobile devices by adjusting padding and margin values to ensure consistent spacing across all screen sizes.
- Fixed the in-app update check URL to use the renamed drinaluza-releases repository.
- Fixed the changelog publishing step and wired it into the production APK build.
- Fixed the development APK build environment flag (local to development).


