# Backdoor: The AI-Native Sui Security Firewall 🛡️💧

An automated, AI-powered transaction guard built for the Sui Blockchain. Backdoor automatically intercepts dangerous dApp interactions, transaction approvals, and wallet connections, using Gemini 1.5 Pro to warn users of vulnerabilities before they sign.

## 🚀 Key Features
- **Auto-Intercept Firewall:** Automatically pops up the moment a user attempts to connect a wallet or approve a transaction on a Sui dApp.
- **Sui Move Object Analysis:** Gemini 1.5 Pro instantly scans the target Move packages and transaction blocks to see exactly what assets are being moved.
- **Plain-English Warnings:** Translates complex Sui Move execution paths into: *"If you sign this, this site can take your Sui NFTs."*
- **Real-Time Telemetry:** Sends fallback threat alerts to users via Telegram if a protocol they hold assets in changes state on-chain.

## 🛠️ Tech Stack
- **AI Engine:** Google Gemini 1.5 Pro
- **Blockchain Target:** Sui Network (Move Language)
- **Backend Framework:** FastAPI (Python) using Sui Python SDK wrappers
- **Frontend Interfacing:** Chrome Extension Manifest V3 (Content Scripts for auto-popups)
