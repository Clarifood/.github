
<div align="center">
  <h1>Clarifood</h1>
  <p><strong>Know what you eat. Anywhere in the world.</strong></p>
</div>

---

## What is Clarifood?

Clarifood is a mobile app (iOS & Android) that lets you scan any food product 
barcode or take a photo of an ingredient label and instantly know if the 
substances inside are legally allowed in the EU, USA, or other regions.

Built for European travelers in the US, American consumers wanting EU-level 
food safety standards, and anyone who wants clarity about what is in their food.

---

## How it works

1. **Scan** — point your camera at a barcode or ingredient label
2. **Check** — we verify every substance against official EU and FDA databases
3. **Know** — get an instant clear result per substance

---

## Our roadmap

| Phase | Focus | Status |
|---|---|---|
| 1 | EU + FDA legal compliance | 🔨 In progress |
| 2 | Organic certification grade | 🔜 Planned |
| 3 | Health score (EFSA / WHO) | 🔜 Planned |

---

## Our services

| Repo | Description |
|---|---|
| [clarifood-mobile](https://github.com/Clarifood/clarifood-mobile) | iOS + Android app (React Native + Expo) |
| [clarifood-gateway](https://github.com/Clarifood/clarifood-gateway) | API Gateway — routing, auth, rate limiting |
| [clarifood-auth-service](https://github.com/Clarifood/clarifood-auth-service) | Authentication — JWT + OAuth2 |
| [clarifood-product-service](https://github.com/Clarifood/clarifood-product-service) | Barcode lookup via Open Food Facts |
| [clarifood-substance-service](https://github.com/Clarifood/clarifood-substance-service) | EU + FDA compliance checker |
| [clarifood-ocr-service](https://github.com/Clarifood/clarifood-ocr-service) | Photo → ingredient text via OCR |
| [clarifood-user-service](https://github.com/Clarifood/clarifood-user-service) | User profiles and scan history |
| [clarifood-notification-service](https://github.com/Clarifood/clarifood-notification-service) | Push notifications and alerts |
| [clarifood-data-sync](https://github.com/Clarifood/clarifood-data-sync) | Daily EU + FDA substance list updater |
| [clarifood-data](https://github.com/Clarifood/clarifood-data) | EU + FDA substance datasets |
| [clarifood-infra](https://github.com/Clarifood/clarifood-infra) | Docker, Kubernetes, Terraform |
| [clarifood-docs](https://github.com/Clarifood/clarifood-docs) | Architecture, API specs, decisions |

---

## Tech stack

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker)

---

<div align="center">
  <sub>Built with care for food transparency worldwide</sub>
</div>
