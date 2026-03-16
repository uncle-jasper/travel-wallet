# ✈️ Travel Wallet

A mobile-first currency converter and travel expense tracker. Convert currencies in real time, log what you're spending on, organise items into folders, and keep your most-used currencies one tap away.

Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no app store required.

---

## Features

**Convert**
- 💱 Live exchange rates powered by [Open Exchange Rates](https://open.er-api.com)
- ⭐ Star up to 8 currencies to pin them to your list
- ✏️ Tap any conversion amount to edit it inline — all other currencies update instantly
- 🏠 Drag any conversion card onto the "I have" section to set it as your base currency
- ▾ Expand / collapse your list — collapsed mode shows your top currency only
- Long-press and drag any card to reorder using insert-gap snapping
- Currency amounts formatted correctly per locale — JPY, KRW, TWD, THB and others display as whole numbers
- 80+ currencies across all regions

**⚙ Unit Converter Drawer**
- Tap ⚙ in the Conversions header to reveal a compact drawer — tap again to hide
- 🕐 **Time** — live clocks for local and home timezone, ticking every second. AM/PM toggle persists across sessions. Tap ⌂ to set current timezone as home
- 🌡️ **Temp** — °C ↔ °F. Tap ◎ to auto-fetch current temperature and location via GPS. Location name appears inline next to Temp. Refreshes automatically after 30 minutes if you've moved
- 📏 **Dist** — km ↔ mi
- ⚖️ **Weight** — kg ↔ lb

**Item Tracker**
- Log item names and prices in any currency while you're out
- Every item shows what you paid (original currency) with your home currency equivalent dimmed alongside
- Extra starred currencies appear as conversion pills below each item
- Date-stamped with the time you logged each purchase (`Mar 15 · 14:32`)
- Drag to reorder items — including within folders
- Swipe left from the Convert tab to reach the tracker instantly
- 🗑 **Clear trip** — wipe everything at end of trip with a 15-second undo window

**Folders**
- Group items into collapsible folders with custom names and emojis
- Tap a folder emoji to change it inline via a popover picker
- Long-press the folder header to drag and reorder folders
- Drag items into folders, between folders, or drop onto the eject zone to remove from a folder
- Drop one loose item onto another to auto-create a new folder from both
- Rename folders inline — tap ✏️, type, press Enter or tap away
- Deleting a folder moves its items back to the loose list

**Running Totals**
- Totals bar shows your grand total across all items
- Tap the currency selector next to the total to view everything in any of your starred currencies
- Expand the totals bar for a per-folder breakdown
- Folder header pills show item count and subtotal at a glance
- All totals update instantly when you change the display currency

**Undo Delete**
- Deleting an item or folder shows a 4.5-second undo toast
- Clear trip gives a 15-second undo window
- Tap Undo any time before it expires to restore everything exactly as it was
- Progress bar in the toast drains visually so you know how long you have

**Design**
- 🌙 Dark mode with a toggle — auto-detects your system preference
- JetBrains Mono throughout for a clean, technical feel
- Full-width drag ghosts at 72% opacity — see what's underneath while dragging
- Fully responsive and touch-optimised for mobile

**PWA**
- 📱 Installable on iPhone and Android — works like a native app
- Offline support via service worker — app loads without a connection, rates refresh when back online

---

## Install on iPhone

1. Open `https://uncle-jasper.github.io/travel-wallet` in **Safari**
2. Tap the **Share** button ↑
3. Tap **"Add to Home Screen"**
4. Tap **Add** — done, it's on your home screen

> Works best in Safari. Chrome on iOS does not support PWA installation.

---

## Install on Android

1. Open the URL in **Chrome**
2. Tap the **three-dot menu**
3. Tap **"Add to Home Screen"** or **"Install App"**

---

## Changelog

### v1.3.1
- Time blocks always same size — boxes stretch to match each other regardless of content
- Separator dot always vertically centred between time blocks
- Local time never shows a day label — only home shows Tomorrow / Yesterday when needed
- "Use current" button in home timezone picker — one tap to detect and save device timezone
- Searchable timezone picker in about modal replaces dropdown
- Unit converter drawer open/close is snappier (0.2s)
- Unit converter fields even on iOS — fixed flex layout

### v1.3.0
- ⚙ Unit converter drawer — Time, Temp, Distance, Weight in a collapsible panel
- Live dual clocks (Local / Home) with AM/PM toggle and DST-aware via Intl API
- Auto temperature via GPS using Open-Meteo (free, no API key) with 30-minute location cache
- Reverse geocoding via Nominatim — location name shown inline next to Temp label
- Set home timezone with ⌂ button, persists across sessions
- 🗑 Clear trip button with 15-second undo window
- 50+ new currencies added — Africa, Middle East, South Asia, Eastern Europe, Americas, Central Asia
- Drag to reorder items within folders
- Disabled text selection during drag gestures on iOS

### v1.2.1
- Full-width drag ghosts at 72% opacity — see what's underneath while dragging
- Correct decimal formatting per currency — JPY, KRW, TWD, THB, MXN, INR and others display as whole numbers
- Drag-to-set-base currency — drag any conversion card onto the "I have" section
- Folder emoji picker — tap any folder emoji to change it inline

### v1.2.0
- Inline amount editing on conversion cards — tap any value to edit, all others update live
- Gap-based drag reorder for currency cards
- Collapsible folders with drag-to-reorder, rename, and eject zone
- Drag items between folders, auto-group two loose items into a new folder
- Running totals bar with per-folder breakdown and inline currency selector
- Undo-delete with animated progress toast
- Date stamps on every item
- Swipe navigation between Convert and Item Tracker tabs

### v1.0.0
- Live exchange rates with refresh timestamp
- Star up to 8 currencies
- Item price tracker with multi-currency display
- Dark mode with system preference detection
- PWA — installable and offline-capable

---

## Credits

Vibe coded by Dan · © 2026  
[☕ Buy me a coffee](https://buymeacoffee.com/dandanmian)
