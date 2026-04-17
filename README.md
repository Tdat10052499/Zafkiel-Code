# Zafkiel-Code - AI-Powered Cinematic Component Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB.svg?logo=react)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg?logo=tailwind-css)
![Celo](https://img.shields.io/badge/Built_on-Celo-35D07F.svg)

**Zafkiel-Code** is a lightweight, Web3-integrated Mini App designed to manipulate time for developers by instantly generating high-quality, "Cinematic" React components via AI text prompts. Built specifically for the MiniPay ecosystem, it introduces a seamless micro-transaction model for cutting-edge AI tools.

## Overview

Developers and designers often need quick UI scaffolding that goes beyond standard, flat designs. Zafkiel-Code solves this by generating code optimized for a specific aesthetic: **Dark themes, minimalist structures, and high-end glassmorphism (Liquid Glass)**, accented with an elegant Crimson and Gold color palette. 

Instead of expensive monthly subscriptions, Zafkiel-Code leverages the Celo blockchain via **MiniPay** to offer a pay-per-use model. Users pay a micro-fee (e.g., 0.05 cUSD) per generation, saving hours of coding time for fractions of a cent.

## Key Features

- **Prompt-to-Code:** Generate ready-to-use React + Tailwind CSS components from simple text descriptions in seconds.
- **Cinematic Aesthetic By Default:** All generated code adheres to an elegant, high-contrast dark mode with glassmorphism effects.
- **Web3 Micro-transactions:** Seamless payment flow integrated directly with the Opera MiniPay wallet. Sub-cent gas fees powered by the Celo network.
- **Frictionless UX:** No login, no credit cards. Connect your MiniPay wallet, enter a prompt, pay, and get your code.

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS (Custom configured for Elegant typography and Liquid Glass effects).
- **Web3 / Payments:** MiniPay SDK, Celo Blockchain (cUSD).
- **AI / LLM:** OpenAI API / Gemini API (For real-time code generation logic).
- **Typography:** Cormorant Garamond (Headings), JetBrains Mono (Code Blocks).

## How It Works

1. **Input:** The user types a UI requirement (e.g., "A pricing card with a glowing crimson border").
2. **Transaction:** The app requests a 0.05 cUSD payment via the MiniPay provider.
3. **Verification & Generation:** Once the smart contract transaction is confirmed, the backend triggers the LLM with a strictly defined System Prompt.
4. **Output:** The rendered code is displayed in a sleek, copyable code block.

## Getting Started

### Prerequisites
- Node.js (v18+)
- A MiniPay Wallet (installed via Opera Mini) on your mobile device for testing.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/zafkiel-code.git](https://github.com/Tdat10052499/Zafkiel-Code.git)
   cd zafkiel-code