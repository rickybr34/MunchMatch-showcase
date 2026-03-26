<p align="center">
  <strong>MunchMatch</strong><br/>
  Decide where to eat — solo or with your group — with swipe-based voting and a clear winner!
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-iOS-000000?logo=apple&logoColor=white" alt="iOS" />
  <img src="https://img.shields.io/badge/UI-SwiftUI-0066CC?logo=swift&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase&logoColor=black" alt="Firebase" />
</p>

---

## Overview

have you or your friends ever been hungry and you both said "where do you want to eat" and go back and forth? Well now you and or your friends can decide on where to eat together. Tis an iOS app for choosing restaurants without the endless group chat. It supports **solo discovery** and **group sessions**: create or join a room, share preferences, swipe on place cards (Tinder-style), vote, and land on a **single winner** everyone can open together.

The app is in **active development**, targeting **TestFlight** first, then the **App Store**.

> **Source code:** The production codebase is maintained in a **private** repository. This public repository is a **product and portfolio showcase** only — screenshots, optional demo media, and high-level documentation. It does not contain the app’s Swift/Xcode sources, API keys, or proprietary implementation details.

---

## Features

- **Solo mode** — Find and filter places near you using location-aware search and find local restaurants!  
- **Group rooms** — Create or join a session with a code; optional sharing via link or QR-style flows where supported.  
- **Preferences** — Capture cravings and filters so suggestions match what the group wants.  
- **Swipe voting** — Card-based UI for fast yes/no decisions on restaurants.  
- **Consensus** — Aggregated votes and a **final winner** screen for the group.  
- **Polished SwiftUI experience** — Designed for clarity, momentum, and real-world use with friends.

---

## Technical highlights

| Area | Approach |
|------|-----------|
| **Client** | SwiftUI with a centralized app model coordinating navigation, room state, and async operations |
| **Realtime collaboration** | Firebase-backed sync for room membership, preferences, and voting lifecycle |
| **Places data** | Google Places–powered discovery and details |
| **Identity & messaging** | Firebase Authentication; push notifications where enabled for session updates |
| **Quality** | Analytics and crash reporting for stability toward public release |

---

## Status

| Milestone | State |
|-----------|--------|
| Core product | In development |
| **TestFlight** | Planned / in progress |
| **App Store** | Planned after TestFlight |

---

## Roadmap

- Device and iOS version coverage  
- TestFlight iteration  
- App Store submission, privacy labels, support content  

---

## Screenshots

<p align="center"></p>

---

## Links

| Resource | URL |
|----------|-----|
| **TestFlight** | — |
| **App Store** | — |
| **Privacy policy** | — |
| **Portfolio** | — |

---

## Layout

```
README.md
LICENSE
assets/
screenshots/
demo/
```

---

## License

MIT — see `LICENSE`.

---

*MunchMatch is an independent project. Google, Firebase, Apple, and other trademarks belong to their respective owners.*
