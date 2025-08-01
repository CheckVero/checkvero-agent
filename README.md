# ✅ Check Vero Agent — Public Signal Verification Interface

This is the web-based agent interface for Check Vero — the AI-native trust layer for digital communication.

Designed to verify **real-time communication signals** — including phone calls, AI output and platform messages — this agent connects users to the decentralized backend infrastructure of Check Vero, built on the Internet Computer (ICP).

## 🧩 Features

- 🌐 Public-facing verification UI (for signal recipients and observers)
- 🔗 Built to connect to Emergent.sh or other agentic backends
- ✅ Designed for production deployment at `checkvero.com`
- 🚀 Fully compatible with persistent API architecture (Vercel-ready)
- 🧠 Includes sample signal data for demo/test environments
- 🛡 Secure, modular, and designed for scaling

## 📂 Folder Structure

- `/public` — Static frontend assets
- `/vercel-backend` — Python FastAPI backend (persistent)
- `/api` — Optional endpoint logic for custom extensions

## 🧠 Use Case (Production Deployment)

- Real-time verification of phone numbers or agent interactions
- Cross-checks against Check Vero Trust Registry (via backend API)
- Returns **✅ Verified** or **❌ Unverified** with source metadata
- CORS-ready for frontends like `checkvero.com` or partner sites
- Supports real-time logging and auditing of verification attempts

## 🚀 Deployment Instructions

1. Deploy the frontend to Vercel (`checkvero.com`)
2. Deploy the backend API to Vercel (`checkvero-api.vercel.app`)
3. Set your environment variable:
4. Link domain(s) via Vercel dashboard
5. Optional: Embed within Emergent.sh or agentic gateway

## 🧱 Built on the Internet Computer (ICP)

✅ Modular architecture (MVP uses Plug Wallet + FastAPI)  
✅ Signal verification anchored via on-chain registries  
✅ Designed for DAO governance & decentralized identity  
✅ Future-proof: Email, AI-agent and chat verification extensions in roadmap  
✅ Part of the Check Vero grant submission to DFINITY (2025)  

---

## 🌐 Learn more

- 🌍 [checkvero.org](https://checkvero.org)
- 🌍 [checkvero.com](https://checkvero.com)
- 
Let’s make trust verifiable and unstoppable.
