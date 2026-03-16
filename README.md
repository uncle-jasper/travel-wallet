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
- Timestamps show when rates were last refreshed, with a manual refresh button
- Currency amounts formatted correctly per locale — JPY, KRW, TWD, THB and others display as whole numbers

**Item Tracker**
- Log item names and prices in any currency while you're out
- Every item shows what you paid (original currency) with your home currency equivalent dimmed alongside
- Extra starred currencies appear as conversion pills below each item
- Date-stamped with the time you logged each purchase (`Mar 15 · 14:32`)
- Swipe left from the Convert tab to reach the tracker instantly

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

### v1.2.2
- Disabled text selection during drag gestures on iOS — no more copy/paste popover while reordering

### v1.2.1
- Full-width drag ghosts at 72% opacity — see what's underneath while dragging
- Correct decimal formatting per currency — JPY, KRW, TWD, THB, MXN, INR and others display as whole numbers
- Drag-to-set-base currency — drag any conversion card onto the "I have" section (replaces long-press, fixes iOS conflict)
- Folder emoji picker — tap any folder emoji to change it inline

### v1.2.0
- Inline amount editing on conversion cards — tap any value to edit, all others update live
- Gap-based drag reorder for currency cards — consistent with item tracker behaviour
- Collapsible folders with drag-to-reorder, rename, and eject zone
- Drag items between folders, auto-group two loose items into a new folder
- Running totals bar with per-folder breakdown
- Inline currency selector on totals — switch display currency without affecting base
- Undo-delete with animated progress toast (4.5s window)
- Date stamps on every item (`Mar 15 · 14:32`)
- Swipe navigation between Convert and Item Tracker tabs
- Consistent item card layout — original currency always primary, base currency dimmed

### v1.0.0
- Live exchange rates with refresh timestamp and manual refresh button
- Star up to 8 currencies — favorites drive the whole UI
- Collapse / expand list — top currency always shown when collapsed
- Item price tracker — logs in any currency, displays in current base
- Dark mode with system preference detection
- PWA — installable and offline-capable

---

## Credits

Vibe coded by Dan · © 2026  
[☕ Buy me a coffee](https://buymeacoffee.com/dandanmian)
