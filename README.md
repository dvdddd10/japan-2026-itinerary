# 🎌 Project Japan 2026 // 日本の冒険

A self-contained, interactive single-page application built to track and manage an 11-day trip to Japan (Tokyo, Kyoto, Osaka, Nara, and Mt. Fuji)[cite: 1]. 

Designed for mobile-first usability on the go, it features offline-capable fallbacks, live currency conversion, and dynamic timeline tracking[cite: 1].

## ✨ Features

*   **Smart Itinerary:** Day-by-day interactive timeline with collapsible time blocks and activity categorization (JDM, Anime, Nightlife, etc.)[cite: 1].
*   **Live Currency Converter:** Real-time MYR (RM) to JPY (¥) conversion using multiple API fallbacks (currency-api, jsDelivr, Frankfurter), ensuring it works gracefully even if a CDN goes down[cite: 1].
*   **Dual Timezones:** Live clocks tracking JST (Japan) and MYT (Malaysia) simultaneously[cite: 1].
*   **Trip Budget Tracker:** Built-in expense logger that stores data locally in the browser (`localStorage`) to track spending on the fly[cite: 1].
*   **Travel Survival Kit:** Includes a Japanese phrasebook, train line cheat sheet, emergency contacts, and a packing checklist[cite: 1].
*   **Dark/Light Mode:** Toggleable theme support saving user preferences locally[cite: 1].
*   **Easter Eggs:** Konami code implementation and hidden interactive elements[cite: 1].

## 🛠️ Tech Stack

*   **HTML5** (Single-file architecture for simple deployment)[cite: 1]
*   **Vanilla JavaScript (ES6)** (Zero external dependencies)[cite: 1]
*   **CSS3** (Custom variables, responsive grid/flexbox layouts, CSS animations)[cite: 1]

## 🚀 Deployment (Cloudflare Pages)

This project is optimized for automated deployment via Cloudflare Pages using GitHub integration.

1. Fork or clone this repository.
2. Ensure the main HTML file is named exactly `index.html` in the root directory.
3. Log into [Cloudflare Pages](https://pages.cloudflare.com/).
4. Select **Connect to Git** and choose this repository.
5. Leave the build command and build output directory **blank** (since it's a static HTML file).
6. Click **Save and Deploy**. 

Any future commits pushed to the `main` branch will automatically trigger a new deployment.

## 📱 Usage on Mobile

For the best experience during the trip:
1. Open the deployed Cloudflare URL in Safari (iOS) or Chrome (Android).
2. Tap **Share** > **Add to Home Screen**.
3. The app will launch in full-screen mode like a native application thanks to the `apple-mobile-web-app-capable` meta tag[cite: 1].
