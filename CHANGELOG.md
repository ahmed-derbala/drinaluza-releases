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
