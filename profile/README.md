# Safely

Safely is a fraud-detection and trust platform for online marketplaces. It analyzes listings and sellers in real time — before you send a single payment — and warns you when something looks like a scam.

Instead of trusting a listing on faith, Safely reads the seller's history, cross-references community fraud reports, and runs the listing through AI-powered signal detection to give you a clear risk score and a plain-language explanation of why.

## 🚀 Features

- **Real-time risk scoring** — every listing gets a 0–100 risk score the moment you open it
- **AI-powered signal detection** — urgency language, advance-payment requests, fraud pattern matching, price-vs-market analysis, and more, powered by Claude
- **Seller trust profiles** — account age, verification status, and visit activity for every seller you check
- **Community fraud reporting** — buyers report scams directly from the extension, instantly protecting the next person who views that seller
- **Cover Status** — sellers are marked Unverified or Reported based on real community reports, not an algorithm's guess
- **Dashboard** — a full history of every listing you've checked and every report you've filed, sign in with email (magic link) or Google
- **Works across marketplaces** — OLX Pakistan live today, Facebook Marketplace and others planned

## 🌍 Vision

Safely aims to become the trust layer for online marketplaces — a browser extension that quietly protects every transaction you make, backed by a community of buyers who report fraud as they encounter it.

## 🛠 Tech Stack

- **Backend** — Rust, Axum, PostgreSQL, sqlx
- **Extension** — Vanilla JS, WebAssembly (Rust/wasm-bindgen), Chrome Manifest V3
- **Web** — Tailwind CSS, plain HTML/CSS/JS (landing page and dashboard)
- **AI** — Anthropic Claude API for listing and signal analysis
- **Auth** — Email magic links (via Resend) and Google OAuth
- **Email** — Resend

## 🤝 Contributing

Contributions, ideas, and feedback are welcome.
