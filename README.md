# Vkusodex

### Collect the tastes you've tried.

**Discover. Collect. Complete.**

A cross-platform food collection app that turns trying new snacks, drinks, and flavors into a rewarding experience.

**React Native · Expo · TypeScript · SQLite**

*Product Showcase · Documentation Only*

---

## The Idea

What if discovering new food felt like completing a collection?

Vkusodex lets users explore curated collections of snacks, drinks, and regional flavors from around the world.

Try something new, mark it as discovered, track your progress, and unlock achievements as your collection grows.

It's a personal food passport — built around curiosity, exploration, and the satisfaction of completing a set.

## App Experience

### 01. Discover Collections

Browse curated food and beverage collections, explore categories, and search for products you've tried or want to discover.

Each collection has its own identity, visual presentation, and completion progress.

### 02. Complete a Collection

Mark individual products as tried and track your progress toward completing a set.

Record when you tried something, review what's missing, and see your progress update.

### 03. Progress & Achievements

Turn food discoveries into measurable progress:

- Track tried products and completed collections.
- Earn experience points and unlock levels.
- Discover achievements based on your activity.
- Review your personal tasting history.

### 04. Share Your Collection

Create shareable collection cards that showcase your progress and discoveries.

Export the result as an image through your device's native sharing interface.

**Product screenshots:** Four real application screens will be added after capture and asset review.

## Key Features

- Curated food and beverage collections
- Product search and category filtering
- Personal tasting journal
- Collection completion tracking
- XP, levels, and achievements
- Offline local data storage
- Backup and restore
- Shareable collection images
- English and Russian localization
- Light and dark appearance

## Built for Offline Use

Vkusodex keeps the core collection experience available without requiring a backend connection.

User activity is stored locally, while collection progress and achievements are calculated from that activity.

This design keeps the current experience lightweight and makes it possible to evolve the data model toward future synchronization.

## Technology

| Area | Technology |
|---|---|
| Mobile | React Native, Expo |
| Language | TypeScript |
| Navigation | Expo Router |
| Local Storage | SQLite |
| Data Validation | Zod |
| Domain Logic | Shared TypeScript packages |
| Localization | i18next |
| Testing | Vitest |
| CI | GitHub Actions |

## Behind the Experience

The application is designed around several engineering principles:

**Event-based activity tracking** — User actions are represented as immutable events.

**Derived progress** — Collection completion, XP, levels, and achievements are calculated from recorded activity.

**Shared business logic** — Domain rules are separated from the UI and storage implementation.

**Structured content pipeline** — Curated catalog data is validated and built into an application-ready snapshot.

**Reliable local persistence** — SQLite provides persistent storage, with export and restore functionality.

Read the [Architecture Documentation](docs/architecture.md) for more details.

## Development Status

**Early-stage mobile application — active development**

The current application focuses on curated collections, personal tracking, achievements, and offline persistence.

Accounts, cloud synchronization, social features, recipes, and barcode scanning are potential future capabilities, not part of the current implementation.

## Source Code

This is a public, documentation-only product showcase.

The original application source code, private development assets, and internal configuration are maintained separately.

---

**Created by Roman Agadjanyan**

Software Engineer

[GitHub](https://github.com/comebackunreal) · [LinkedIn](https://www.linkedin.com/in/laeslow/)
