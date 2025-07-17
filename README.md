# Flutter Steam Inventory & Trade Viewer

[![Awesome Flutter](https://img.shields.io/badge/Awesome-Flutter-blue.svg)](https://github.com/Solido/awesome-flutter)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)

> A clean and elegant **Steam Inventory Manager** built with Flutter, allowing users to browse, search, and manage their virtual items and trades directly from the Steam platform — optimized for gamers, traders, and collectors.

---

## 🎮 App Features

- 🧳 **Inventory Viewer**  
  Display your Steam items (CS:GO skins, Dota 2, TF2 hats...) with icons, names, prices, wear levels, and more.

- 🔍 **Advanced Search & Filter**  
  Filter items by rarity, game, type, and price range. Search by keyword or partial name.

- 💹 **Market Price Integration**  
  View real-time prices using Steam Community Market APIs. See fluctuations and price history (if supported).

- 💱 **Trade Offer Management**  
  View, send, and manage trade offers. Preview items in each trade and confirm actions securely.

- 🔐 **Steam OAuth Login**  
  Secure authentication using Steam OAuth to access private inventory and manage trades.

- 📱 **Modern Flutter UI**  
  Responsive, animated UI built with Flutter. Supports light/dark themes, smooth transitions, and clean architecture.

---

## 📸 Screenshots

| Inventory | Item Details | Trade Preview |
|----------|---------------|----------------|
| ![Inventory](screenshots/inventory.png) | ![Item](screenshots/item-details.png) | ![Trade](screenshots/trade-preview.png) |

> _Note: Replace with your own screenshots as needed._

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed → [Install Flutter](https://flutter.dev/docs/get-started/install)
- Steam API Key → [Get one here](https://steamcommunity.com/dev/apikey)

### Installation

```bash
git clone https://github.com/dearvn/flutter_steam.git
cd flutter_steam
flutter pub get
flutter run
