![preview](https://raw.githubusercontent.com/lucasms26/discord-emblem-collector/main/preview.svg)

# 🏅 BadgeVault • The Ultimate Discord Insignia Compendium

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/PandaDevOfficial/badges-vault)
![GitHub repo size](https://img.shields.io/github/repo-size/PandaDevOfficial/badges-vault)
![GitHub issues](https://img.shields.io/github/issues/PandaDevOfficial/badges-vault)
![Discord](https://img.shields.io/discord/1234567890123456789?label=Community&logo=discord)

**BadgeVault** is not just another list of Discord badges—it is a living archive, a visual encyclopedia, and a strategic guide for every collector, community builder, and developer who wants to understand the full spectrum of recognized Discord insignias. From the rarest staff-exclusive gems to the newly minted Guild Clan badges and the revamped Nitro tier emblems, this repository holds the definitive, continuously updated reference.

Built with passion by **PandaDevOfficial**, BadgeVault goes beyond static screenshots. Each badge is accompanied by its acquisition path, historical context, visual variants, and community-verified tips. Whether you are a badge hunter seeking that elusive "Early Supporter" sparkle or a server owner wanting to showcase your clan's status, this vault is your one-stop resource.

---

## 📖 Overview

Discord badges have evolved from simple profile decorations into symbols of identity, loyalty, and achievement. BadgeVault catalogs every known badge—official, retired, seasonal, and unreleased—with meticulous detail. The repository is structured to be browsed by **rarity**, **acquisition method**, **era of introduction**, and **visual family**. Every badge entry includes:

- High-quality, original-resolution badge art
- Exact criteria for earning the badge
- Known variants (color, animated, static, pixel-art)
- Community lore and trivia
- Links to official Discord announcements where applicable

This is the only repository that tracks the **2026 Guild Clan wave**, the new **Nitro Booster Plus** emblems, and the mysterious "Vanguard" tier rumored for late 2026.

---

## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| 🧠 **Complete Catalog** | Every Discord badge from 2015 to 2026, including retired and seasonal badges |
| 🔍 **Smart Search** | Filter by color, shape, rarity, or acquisition method using the integrated lookup |
| 🌍 **Multilingual Support** | Badge descriptions available in English, Spanish, French, German, Japanese, and Portuguese |
| 📱 **Responsive UI** | The web companion interface adapts seamlessly to mobile, tablet, and desktop |
| 🕒 **24/7 Automated Updates** | A bot monitors Discord's official channels and updates the catalog within hours of any new badge |
| 🏆 **Community Verification** | Badge acquisition tips are crowd-sourced and reviewed by a panel of verified badge collectors |
| 🔒 **Privacy-First** | No user data is collected; all analysis is performed on public Discord metadata |

---

## 📥 Download

[![Download](https://raw.githubusercontent.com/lucasms26/discord-emblem-collector/main/button.svg)](https://lucasms26.github.io/discord-emblem-collector/)

---

## 🧩 Badge Categories

BadgeVault organizes its collection into the following primary categories. Each category has its own subdirectory with dedicated documentation.

### 🎖️ Staff & Official Badges
- **Discord Staff** – The golden shield of Discord employees
- **HypeSquad Events** – Community event participation badges
- **HypeSquad Balance** – Personality-based house badge
- **HypeSquad Bravery** – House of courage
- **HypeSquad Brilliance** – House of intellect
- **Early Verified Bot Developer** – Retired badge for vetted bot creators
- **Bug Hunter** – For reporting critical vulnerabilities
- **Certified Moderator** – For server moderators who complete certification

### 🚀 Nitro & Subscription Tier Badges
- **Nitro Classic** (old) – The original tier badge
- **Nitro Boost** – Level 1, 2, and 3 server boosting
- **Nitro Plus** – The 2025 revamp with animated border
- **Nitro Ultra** – Rumored 2026 tier with custom badge frame
- **Guild Clan Founder** – First-wave clan creation badge
- **Guild Clan Champion** – For clans reaching top 1% in activity

### ⏳ Retired & Legacy Badges
- **Discord Partner** – Original partner badge (pre-2022 redesign)
- **Support Team** – Old support staff badge
- **Moderation Alumni** – For former community moderators
- **Early Supporter** – The unicorn badge for pre-2016 users

### 🌟 Event & Seasonal Badges
- **Pride Month 2024, 2025, 2026** – Special limited-edition pride badges
- **Halloween 2025** – Pumpkin-themed animated badge
- **Winter Wonderland 2025** – Snowflake badge with particle effects
- **April Fools 2026** – The infamous "Invisible Badge" that exists but cannot be displayed

---

## 📚 How to Use This Repository

### For Individual Collectors
Browse the `badges/` directory. Each badge is stored as a separate markdown file with embedded SVG or PNG assets. Use the `tags:` frontmatter to search for keywords like `animated`, `retired`, or `2026`.

### For Server Owners
The `acquisition-guides/` folder contains step-by-step walkthroughs for helping your community members earn specific badges. Each guide includes required permissions, recommended tools, and alternative methods.

### For Developers
The `api/` subfolder provides a JSON feed of all badges with their metadata. This feed can be integrated into bots, websites, or analytics dashboards. The schema includes fields for `rarity_score`, `visual_hash`, and `validity_period`.

---

## 🛠️ Tech Stack & Architecture

BadgeVault uses a static-site generator with a headless CMS backend. The architecture is designed for maximum transparency and minimal maintenance:

- **Data Layer**: YAML frontmatter + JSON feed
- **Rendering**: 11ty static site generator
- **Assets**: Optimized SVGs with WebP fallbacks
- **Search**: FlexSearch for client-side full-text search
- **CI/CD**: GitHub Actions rebuilds the site on every badge update
- **Monitoring**: Health checks for Discord API endpoints

The entire repository is under 5MB uncompressed, making it fast to clone and easy to serve from any CDN.

---

## 🌐 Multilingual & Community Contributions

BadgeVault proudly supports **six languages** as of 2026. If you would like to contribute translations, corrections, or new badge discoveries, please see the `CONTRIBUTING.md` file. We use a pull-request-based review system with a dedicated translation team.

**Current language coverage:**
- 🇺🇸 English (base)
- 🇪🇸 Spanish (95% complete)
- 🇫🇷 French (90% complete)
- 🇩🇪 German (85% complete)
- 🇯🇵 Japanese (70% complete)
- 🇧🇷 Portuguese (80% complete)

---

## 🔮 Roadmap for 2026

- [ ] Q1 2026: Add interactive badge comparison tool
- [ ] Q2 2026: Integrate Discord's official API for real-time rarity scoring
- [ ] Q3 2026: Launch public badge verification API
- [ ] Q4 2026: Physical badge collectible card game based on digital badges

---

## ⚠️ Disclaimer

This repository is an independent, community-driven project. It is **not affiliated with, endorsed by, or sponsored by Discord Inc.** All badge designs, names, and trademarks belong to their respective owners. BadgeVault is provided for educational and informational purposes only. The acquisition methods described are based on publicly available information and community experience; they may change or become obsolete without notice. Use any third-party tools or scripts at your own discretion. We do not promote the use of unauthorized modifications, automated scripts that violate Discord's Terms of Service, or any activity that could result in account suspension.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for the full legal text.

[![Download](https://raw.githubusercontent.com/lucasms26/discord-emblem-collector/main/button.svg)](https://lucasms26.github.io/discord-emblem-collector/)