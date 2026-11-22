# Medium-Real-Time-Follower-Count
A lightweight Node.js tool that uses Puppeteer to bypass Cloudflare and instantly fetch real-time follower counts from Medium profiles.

## ✨ Features
- 🔍 **Flexible Input:** Accepts both Medium usernames (e.g., `@username`) and full Medium profile URLs.
- 🛡️ **Cloudflare Bypass:** Uses Puppeteer with stealth configurations (spoofed User-Agent, disabled webdriver flags) to avoid bot blocks.
- ⚡ **Smart Extraction:** Uses robust Regex patterns to find follower counts in both rendered HTML and hidden JSON script tags.
- 🚀 **Lightweight API:** Returns clean JSON responses, making it easy to integrate into other projects or dashboards.

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Web Scraping:** Puppeteer (Headless Chrome)

