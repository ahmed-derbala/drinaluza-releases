## [1.103.0] - 17 november 2026

- Sharing a link to the web version on Facebook, WhatsApp, Telegram or LinkedIn now shows the app image, title and description.
- The welcome message on the web now shows the app icon and explains the two choices next to the download and close buttons.
- The latest release card no longer shows a copy link button; on the web its share button copies the download link to the clipboard.
- On Android, opening the Updates screen now starts the download automatically when auto update is allowed for your current connection.
- The app now keeps a single update file on your device: a new download replaces the previous one, so old versions never pile up.
- Choosing a language in the welcome message now applies to the whole app, including products and business names.

## [1.102.0] - 16 november 2026

- Requesting a new business now opens a full screen instead of a pop-up, so the form is roomier and easier to fill on phones.
- Business request results now appear in your chosen language.

## [1.100.0] - 15 november 2026

- The app now makes sure a downloaded update is complete before opening the installer, and downloads it again when the file is damaged or incomplete.
- If saving a downloaded update fails, the app now tells you instead of opening a file that does not exist.
- Download speed and remaining time during an update no longer jump between values.
- Update messages, sharing and installation errors now appear in your chosen language.

## [1.99.0] - 15 november 2026

- The web version now welcomes visitors with a short message that recommends the Android app for the best experience.
- The welcome message offers to download the latest Android app and can be dismissed for good.
- Modal titles and subtitles now always sit at the top left, next to the icon, in every language.
- The device now keeps only the latest downloaded update file together with a download in progress, instead of accumulating old installers.

## [1.98.0] - 14 november 2026

- The products list is now the home screen and opens by default when you start the app.
- Product pages opened from the products list keep the same address and navigation as before.
- The separate feed screen has been removed; the products tab now shows the same product cards.
- Starring contacts is no longer required: you can leave every contact unstarred, or pick up to two public contacts to show first.
- Product cards now show a separate button for every starred contact kind (up to two), so SMS, Messenger and other contacts each get their own action.
- The action buttons on product cards keep the same position even when a business has no contacts or no directions available, so the layout no longer jumps between products.
- Product cards now show the business name and address over the photo, so you see who sells the product before opening it.
- Product cards now show only the product size; harvest, gear and origin details are on the product page, and the category label was removed.
- The business that sells a product now appears on the product page as a full card with its photo, address, directions, share and every contact button.
- Business cards in the businesses list now show directions and share only; contact buttons moved to the product cards.
- In view mode, contact information now lists your starred contacts first, in the order you set, instead of a fixed default order.
- Starring a contact now makes it public, so a contact you want to show first can no longer stay hidden.
- Screens across the app now appear fully in Tunisian, in Arabic or Latin letters, instead of falling back to English.
- Search has been removed from the app: the search screen, its button in the feed header and the search field in product lists and pickers are gone.
- Product stock is no longer part of the app: stock quantity, minimum thresholds, low-stock indicators and the related statistics have been removed.
- The weight range of a single fish is now edited in the product specifications instead of the price card.
- The About Business description has been removed from the business edit screen.
- The fish icon that shows a product size on product cards is now fully visible, so it is no longer cut off at the edge.

## [1.97.0] - 9 november 2026

- Contact information is now easier to manage: you can add and edit phone numbers, SMS numbers, WhatsApp, Messenger, Instagram, email and website details, including extra numbers or accounts when needed.
- You can choose 1 or 2 public contacts to show first by starring them.
- WhatsApp, Messenger and Instagram fields now show a fixed link prefix, so you only need to enter the number or username.
- The Messenger icon has been updated.

## [1.93.0] - 31 october 2026

- The app now tells the backend which version and platform it runs on with every request.
- When the backend stops accepting your app version, the app now asks you to update: on Android it opens the updates screen and starts downloading the new version when your update settings allow it, and on the web it refreshes the page. Both show a message so you know why.

## [1.92.0] - 29 october 2026

- Signing in now warns you when the device cannot save your session, instead of looking successful and signing you out later.
- Signing out now clears your saved session from every place it is stored, so an old leftover copy can no longer bring a previous account back.
- The app no longer erases your saved login when a single request fails while it was sent without a login token.
- This update asks you to sign in again once and starts from the default preferences: your session and settings are now stored under clearer names, so the ones saved by the previous version are not reused.

## [1.91.0] - 27 october 2026

- Saved data now stays on your device until fresh data arrives from the backend, so lists, pages, profiles and dashboards open instantly instead of being downloaded again.
- The app no longer treats saved data as out of date after a few minutes: screens keep working offline even days after you last opened them.
- Photos and videos are downloaded once and then reused from the device.
- When the backend is reachable, saved data is still refreshed in the background so what you see stays up to date.
- The storage card was removed from the updates screen, so storage and cache clearing is no longer available there.
- On the web, pages no longer change size after a refresh: cards and lists now appear directly in their final layout instead of being resized a moment later.

## [1.90.0] - 23 october 2026

- The updates screen now shows the app environment on the current release card, so you can tell at a glance whether you are using the development, staging or production version.
- Buttons now keep the same shape and colours everywhere in the app. Screens and cards can no longer change how a button looks, so actions such as sharing, editing or deleting stay easy to recognise.
- Contact buttons for phone, email, website, WhatsApp, Messenger, Instagram and directions now follow the same outlined style as the rest of the app.
- The Messenger contact button now shows the Facebook Messenger logo.
- The environment subtitle was removed from the updates screen header; the environment is now shown on the current release card instead.
- The free-space badge was removed from the Android release card, and the app no longer checks available storage before downloading an update.

## [1.88.0] - 22 october 2026

- The category picker now loads as many items per page as you chose and fetches more pages while you scroll.
- Lists now fit cards to the screen instead of squeezing them: each card keeps a minimum readable width, complex product and business cards take one full-width column on phones, and extra columns appear only on tablets and wider screens where every card still fits comfortably.
- Sales and purchases lists now follow the same card-density rule: order cards keep their minimum readable width while more of them fit per row on larger screens.
- Cards, lists and menus now follow one shared screen-size rule: everything switches to its compact layout at the same screen width and reacts together when you rotate the device, so content no longer gets cut off on small screens.
- On phones, the last cards of the businesses list and some stacked pages no longer sit behind the system navigation bar at the bottom of the screen.
- Big screens now show more content instead of bigger content: dashboard cards, notifications and your businesses lists spread over several columns while every card keeps its readable size, and business and personal dashboards keep their content within a comfortable width instead of stretching edge to edge.
- The feed, products, businesses, search, notifications and dashboard product lists now show every card of a row on wide screens: each card keeps its own place instead of pushing the other cards out of the screen.
- On tablets, desktop windows and other wide screens, cards are laid out at their comfortable size: the available width becomes multiple readable cards, while phones show complex cards in a single full-width column.
- The search box was removed from the category picker: categories are listed page by page with the page size you chose.
- The Basic Information card was removed from the profile screen.
- The Social Media card was removed from the profile screen.

## [1.85.0] - 20 october 2026

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
- The price fields on the create and edit product screens now accept the price in millimes, with a maximum of 9 digits.
- The app language now applies instantly across the whole app when you switch it in the settings screen, without reloading screens or lists.
- Fixed the business page's product strip stopping after the first page when scrolling sideways.
- Fixed the last page of the feed not showing its cards until you reopen the screen.
- Fixed the number of cards in the feed not matching the total count while scrolling.
- Fixed the feed loading twice in a row when you open it, which wasted data.
- Fixed a business page showing only the first 10 products of a business.
- The app now stores less account data on your device (one snapshot instead of several copies of the same details).
- Temporary download progress is no longer saved on your device.
- Language and currency are no longer part of your account: languages are saved on this device and prices are shown in Tunisian dinar.
- The language picker on the sign-in screen was removed — change languages from the new card in the settings screen.
- The Reset App card is removed from the settings screen.
- The QR code scanner is removed from the feed.
