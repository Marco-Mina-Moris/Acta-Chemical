<img width="1536" height="1024" alt="acta-chemical-banner" src="https://github.com/user-attachments/assets/a935447b-effb-4f74-bd21-c230045b9e16" />
<h1 align="center">ACTA Chemical</h1>
<h3 align="center">Your Reliable Chemical Partner — Industrial & Laboratory Chemicals E-Commerce</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter"/>
  <img src="https://img.shields.io/badge/Laravel-Sanctum%20API-red?logo=laravel"/>
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey"/>
  <img src="https://img.shields.io/badge/Architecture-Clean%20Architecture-orange"/>
</p>

---

## About

**ACTA Chemical** is a Flutter e-commerce app built for a chemicals supply company, connecting industrial and laboratory clients with a wide catalog of chemical products — from raw materials to specialty serum-care ingredients.

> "Chemistry for a Better Tomorrow."

Built for **Marketopia**, the app is fully integrated with a real production Laravel backend, supporting bilingual product catalogs, multiple payment methods, and downloadable technical documentation per product category.

---

## Features

### Catalog
- Four main product sections: **Cosmetics**, **Detergents & Cleaners**, **Raw Materials**, and **Specialty Serum-Care Materials**
- Each section includes multiple product types with images and descriptions
- Bilingual product data (Arabic / English)

### Shopping
- Browse categories and products, view details and specifications
- Add to cart, wishlist, and checkout
- Multiple payment methods, including Paymob and cash on delivery

### Resources
- Downloadable technical booklets & guides (PDFs) per product section, so clients can review specs before ordering

### Account
- Authentication and profile management
- Order history and saved addresses

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Flutter (Dart) |
| Backend | Laravel API (Sanctum authentication) |
| Payments | Paymob, Cash on Delivery |
| Architecture | Clean Architecture / Repository Pattern |
| AI-Assisted Dev | Antigravity |

---

## Project Structure

```
lib/
├── main.dart                      # App entry point
├── core/                          # Shared utilities, theming, network client
│   ├── constants/
│   ├── network/
│   ├── routes/
│   └── utils/
│
└── features/                      # Feature modules (Clean Architecture)
    ├── auth/                      # Login, register, profile
    ├── home/                      # Featured products & categories
    ├── catalog/                   # Cosmetics, detergents, raw materials, serum-care
    ├── product_details/           # Product info, specs, and booklet downloads
    ├── cart/                      # Cart management
    ├── checkout/                  # Checkout & payment method selection
    ├── addresses/                 # Saved shipping addresses
    ├── wishlist/                  # Favorites
    └── orders/                    # Order history & tracking
```

---

## API Overview (Laravel Backend)

| Endpoint Group | Description |
|---|---|
| `/api/v1/auth/*` | Register, login, logout, addresses |
| `/api/v1/categories`, `/api/v1/products` | Catalog with EN/AR translations |
| `/api/v1/cart`, `/api/v1/checkout` | Cart & order placement |
| `/api/v1/payment-methods` | Paymob, cash on delivery |
| `/api/v1/wishlist` | Favorites |
| `/api/home`, `/api/events/{id}`, `/api/articles/{id}`, `/api/contact` | Unversioned supporting endpoints |

---

## Getting Started

### Prerequisites
- Flutter SDK 3.x
- Dart SDK
- Android Studio or VS Code
- Access to the ACTA Chemical backend API

### Installation

```bash
git clone https://github.com/MARCO-Develper/acta-chemical.git
cd acta-chemical
flutter pub get
flutter run
```

> Note: This repository contains the project overview only. The full source code is proprietary to Marketopia and the client, and is not publicly available.

---

## Developer

| Name | Role | Contact |
|---|---|---|
| **Marco Mina** | Flutter Developer, Marketopia | [GitHub](https://github.com/MARCO-Develper) \| [LinkedIn](https://www.linkedin.com/in/marco-mina-515369262) |

---

<p align="center">Made with ❤️ by Marco Mina — 2026</p>
