---
layout: default
title: Privacy Policy — tourguide
---

# Privacy Policy

**tourguide** &mdash; last updated March 17, 2026

---

> **Short version:** tourguide does not collect personal information, has no account system, uses no analytics or advertising, and stores all data exclusively on your device. The only external service the app contacts is Wikipedia's public, read-only API.

---

## 1. Overview

tourguide is an iOS app that notifies you when you are near places of historical or cultural significance and provides direct links to their Wikipedia articles. This Privacy Policy explains what information the app uses, how it is used, and your choices.

## 2. Information We Collect

tourguide does **not** create user accounts, assign identifiers, or collect names, email addresses, or any personally identifying information.

The app uses the following information solely to provide its core functionality:

| Data type | Purpose | Stored where |
|---|---|---|
| GPS coordinates | Find Wikipedia articles near your current position | On-device only; sent to Wikipedia API (see §3) |
| Journey records | Log the sites you discover on each walk (name, coordinates, timestamp, Wikipedia URL) | On-device only |
| Route breadcrumbs | Draw your path on the journey map | On-device only |
| App preferences | Remember your search radius, notification settings, and other choices | On-device only |

No data is sent to any server operated by the app developer. There is no backend, no cloud sync, and no iCloud integration.

## 3. Location Data

Location access is the core permission the app requires. When you start a journey (or enable background tracking in Settings), the app uses Apple's CoreLocation framework to receive GPS updates.

Your coordinates are transmitted **only** to Wikipedia's public GeoSearch API (`en.wikipedia.org`) to retrieve a list of geotagged articles near you. This is a standard, anonymous, read-only API call — no account, API key tied to you, or persistent identifier is sent alongside your coordinates.

You can choose between two levels of location access:

- **While Using the App** — location is only used when the app is on screen.
- **Always** — allows the app to continue discovering nearby sites and sending notifications while running in the background. You can toggle this off at any time in iOS Settings → Privacy & Security → Location Services → tourguide.

## 4. Notifications

tourguide requests permission to send local notifications to alert you when you are near a point of interest. All notifications are generated entirely on-device using Apple's UserNotificationCenter framework and do not pass through any external push service or server.

## 5. Third-Party Services

The only external service the app communicates with is:

| Service | Purpose | Data sent | Privacy policy |
|---|---|---|---|
| Wikipedia (Wikimedia Foundation) | Retrieve nearby geotagged articles and article summaries | GPS coordinates (latitude & longitude) | [wikimedia.org/Privacy_policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy) |

The app uses **no** analytics SDKs, advertising networks, crash reporting services, or any other third-party frameworks. It contains no tracking code of any kind.

## 6. Data Retention and Deletion

All journey history, route data, and preferences are stored locally on your device using Apple SwiftData and UserDefaults. You can delete individual journeys from within the app at any time. To remove all app data, delete the app from your device; iOS will remove all associated local storage.

## 7. Children's Privacy

tourguide does not knowingly collect any information from children under 13 (or the applicable age of digital consent in your jurisdiction). The app collects no personal information from any user, including children.

## 8. Changes to This Policy

If this policy changes materially, the updated version will be posted at this URL with a revised "last updated" date. Continued use of the app after changes take effect constitutes acceptance of the revised policy.

## 9. Contact

If you have questions or concerns about this privacy policy, please contact:

[andrewgwoolman@gmail.com](mailto:andrewgwoolman@gmail.com)

---

*tourguide — Privacy Policy — Effective March 17, 2026*
