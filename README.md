# ✈️ Travel Wallet

A mobile-first currency converter built for travelers. Convert currencies in real time, track what you're spending on, and keep your most-used currencies one tap away.

Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no app store required.

---

## Features

**Convert**
- 💱 Live exchange rates powered by [Open Exchange Rates](https://open.er-api.com)
- ⭐ Star up to 8 currencies to pin them to your list
- 🔄 Tap any currency card to instantly swap it as your base — amount converts automatically
- ⇅ Permanent swap button always swaps your top currency instantly
- ▾ Expand / collapse your full list — collapsed mode shows your top currency only
- Drag and hold any card to reorder your currency list
- Timestamps show exactly when rates were last refreshed, with a manual refresh button

**Item Tracker**
- Log item names and prices in any currency while you're out
- Every item displays in your current base currency, with the original price shown as reference
- Conversions update live when you change base currency or expand/collapse your list
- Items persist between sessions

**Design**
- 🌙 Dark mode with a toggle — auto-detects your system preference
- JetBrains Mono throughout for a clean, technical feel
- Fully responsive and touch-optimized for mobile
- Long-press any currency card to drag and reorder

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

### v1.0.0
- Live exchange rates with refresh timestamp and manual refresh button
- Star up to 8 currencies — favorites drive the whole UI
- Tap any currency to swap it as your base, amount converts automatically
- Permanent ⇅ swap button always targets your top currency
- Collapse / expand list — top currency always shown when collapsed
- Drag and hold to reorder currencies
- Item price tracker — logs in any currency, displays in current base
- Item tracker synced to visible currencies and collapse state
- Dark mode with system preference detection
- PWA — installable and offline-capable
- "Vibe coded by Dan" footer (non-negotiable)

---

## Credits

Vibe coded by Dan · © 2026  
[☕ Buy me a coffee](https://buymeacoffee.com/uncle-jasper)
