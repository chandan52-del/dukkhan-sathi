# Dukkhan Sathi 🎙️

### Your Shop. Your Language. Your AI Business Partner.

Dukkhan Sathi is a multilingual, voice-first AI business assistant designed for Indian small shopkeepers, kirana store owners and street vendors.

It helps shopkeepers manage customer credit (Udhaar), record transactions, track outstanding payments and prepare polite payment reminders through natural voice conversations in their preferred language.

Instead of maintaining everything in notebooks or navigating complicated applications, shopkeepers can simply speak to their AI business companion.

---

## 💡 The Problem

Small shopkeepers frequently provide groceries and other products on credit, commonly known as **Udhaar**.

For example, a customer takes ₹300 worth of groceries and promises to pay on Saturday.

Because shopkeepers are busy serving customers, they may:
- Forget to record credit transactions.
- Lose track of who owes them money.
- Forget promised payment dates.
- Find it uncomfortable to ask customers for pending payments.
- Spend unnecessary time maintaining manual records.

Traditional digital applications can also be difficult for users who are less comfortable typing or navigating complex interfaces.

## 🚀 Our Solution

Dukkhan Sathi brings an intelligent voice assistant directly to the shopkeeper.

The shopkeeper can speak naturally, and the application understands the request, confirms the details and saves the information.

### Example interaction

**Shopkeeper:**

"Ramesh ko 300 rupaye udhaar diya, Shanivaar ko dega."

**Dukkhan Sathi:**

"Ramesh owes ₹300. Payment is due Saturday. Should I save this entry?"

After confirmation, the transaction is recorded in the customer's ledger.

The shopkeeper can also ask:

- "Who owes me money?"
- "How much udhaar is pending?"
- "How much did I sell today?"
- "Which payments are overdue?"

## ✨ Key Features

- 🎙️ **Voice-First Interaction:** Record transactions through natural speech.
- 🌐 **Multilingual Support:** Designed for Indian regional languages, with Kannada, Hindi and English as initial implementation priorities.
- 📒 **Digital Udhaar Ledger:** Maintain customer-wise outstanding balances.
- 💰 **Transaction Management:** Record credit, payments, sales and expenses.
- 🔔 **Payment Reminders:** Prepare polite payment reminders in the customer's preferred language.
- 📊 **Business Dashboard:** View daily sales, expenses and outstanding credit.
- 🧠 **AI Understanding:** Interpret natural-language requests and extract relevant transaction details.
- ✅ **Confirmation Before Saving:** Verify important transaction details before updating records.

## 🎯 Target Users

- Small kirana store owners.
- Neighborhood grocery shopkeepers.
- Street vendors.
- Small retail businesses.
- Local merchants who regularly provide goods on credit.

## 🛠️ Technology Stack

The proposed development stack includes:

| Technology | Purpose |
|---|---|
| React + Vite | Frontend application |
| TypeScript | Type-safe development |
| Tailwind CSS | UI styling |
| Node.js + Express | Backend and APIs |
| PostgreSQL | Database |
| Gemini API or compatible AI model | Natural-language understanding |
| Speech-to-Text | Voice recognition |
| Text-to-Speech | Spoken AI responses |
| Docker Compose | Application setup and execution |
| GitHub | Source code and version control |

*Specific AI and speech providers may change depending on availability, performance and cost.*

## 🏗️ How It Works

1. The shopkeeper speaks through the application's microphone.
2. Speech recognition converts the voice into text.
3. The AI identifies the intended action and extracts transaction details.
4. The application validates the information.
5. The shopkeeper confirms the transaction.
6. The backend saves the transaction in the database.
7. The application updates the ledger and responds through voice.

## 🔐 Reliability and Data Safety

- Important financial entries require confirmation before saving.
- The backend validates transaction data.
- API keys are kept outside public source code.
- The application should provide a usable interface even when optional AI services are unavailable.
- Payment reminders are prepared for shopkeeper review before sending.

## 🚀 Getting Started

The following instructions describe the intended development setup. They will apply once the corresponding project files are implemented.

### Prerequisites

- Node.js
- Docker Desktop
- Git
- npm

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/dukkhan-sathi.git

cd dukkhan-sathi
```

### Configure environment variables

Create the required environment files using the provided `.env.example` templates.

Add API credentials only to local environment files. Never commit secret keys.

### Start the application

```bash
docker compose up --build
```

The application should start with a single command, without requiring external AI API keys just to display its main screen.

## 📌 Project Status

**Hackathon Prototype – In Development**

The initial prototype focuses on demonstrating the core Udhaar workflow:

- Customer creation.
- Voice-based credit entry.
- Transaction confirmation.
- Customer-wise outstanding balances.
- Voice-based payment queries.

Additional business-management capabilities will be developed as time permits.

## 🌍 Our Vision

Our vision is to make AI accessible to India's smallest businesses by removing language and technology barriers.

We want every shopkeeper to have a reliable digital business companion that understands their language, remembers their transactions and helps them manage their business more confidently.

**Dukkhan Sathi – Your Shop. Your Language. Your AI Business Partner.**

---

*Built for the Scaler × Wispr Hackathon 2026.*
