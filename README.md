# Zafkiel-Code - AI-Powered Component Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB.svg?logo=react)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg?logo=tailwind-css)
![Ant Design](https://img.shields.io/badge/Ant_Design-5.x-0170FE.svg?logo=ant-design)
![Celo](https://img.shields.io/badge/Built_on-Celo-35D07F.svg)

**Zafkiel-Code** is an enterprise-grade, Web3-integrated Mini App designed to manipulate time for developers. It instantly generates high-quality, "Cinematic" React components via AI text prompts and renders them in real-time. Built to showcase the power of the MiniPay ecosystem, it introduces a frictionless micro-transaction model for cutting-edge AI developer tools.

## Overview

Developers often waste hours scaffolding UI components. Zafkiel-Code solves this by generating ready-to-use code optimized for a specific aesthetic: **Enterprise dashboards infused with high-end glassmorphism (Liquid Glass)**, accented by an elegant Crimson and Gold color palette. 

Instead of expensive monthly AI subscriptions, Zafkiel-Code leverages the Celo blockchain via **MiniPay**. Users pay a micro-fee (0.05 cUSD) per generation. Through Cross-device WalletConnect, users can seamlessly build on their desktop while confirming payments on their mobile MiniPay wallet.

## Key Features

- **Prompt-to-Code Generation:** Generate fully functional React + Tailwind CSS components from simple text descriptions in seconds.
- **Enterprise Dashboard Aesthetic:** Built on Ant Design and customized with Tailwind CSS for a sleek, dark-themed, and highly professional layout.
- **Real-Time Live Preview:** Powered by `react-live`, generated code is instantly compiled and rendered on a split-screen canvas. Users can tweak the code and see UI changes instantly.
- **Cross-Device Web3 Payments:** Desktop-first workflow. Connect via QR code and approve sub-cent transactions directly from the Opera MiniPay app on your phone.

## Tech Stack

- **Frontend:** React, Vite, Ant Design (Enterprise UI Components), Tailwind CSS (Glassmorphism & Utility styling), `react-live` (Live rendering).
- **Web3 / Payments:** WalletConnect, MiniPay Provider, Celo Blockchain (cUSD).
- **AI / LLM:** OpenAI API / Gemini API (For real-time React code generation).
- **Typography:** Cormorant Garamond (Headings), JetBrains Mono (Code Blocks).

## How It Works

1. **Connect:** The user opens the Desktop app and scans the WalletConnect QR code using their MiniPay mobile app.
2. **Input:** The user types a UI requirement into the dashboard (e.g., "A pricing card with a glowing crimson border").
3. **Cross-Device Transaction:** The app triggers a 0.05 cUSD payment request. A confirmation pop-up instantly appears on the user's phone.
4. **Generation & Preview:** Once the smart contract transaction is confirmed, the AI generates the component. The Desktop UI splits into an Editor and a Live Preview canvas, displaying the actual working component.

## Getting Started

### Prerequisites
- Node.js (v18+)
- A MiniPay Wallet (installed via Opera Mini) on your mobile device.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/zafkiel-code.git](https://github.com/Tdat10052499/Zafkiel-Code.git)
   cd zafkiel-code