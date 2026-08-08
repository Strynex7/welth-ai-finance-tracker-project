<<<<<<< HEAD
# Welth — AI Finance Tracker

Welth is a full-stack, AI-powered personal finance and budgeting app built with React Native (Expo). It lets users track accounts, log transactions, set budgets, and use AI to scan receipts and log expenses by voice.

## Features

- 🔐 Secure authentication with Clerk
- 💳 Multiple accounts (Bank, Cash, Credit Card, Savings)
- 📊 Dashboard with income/expense charts
- 🧾 AI-powered receipt scanning (Google Gemini)
- 🎙️ Voice-based transaction entry
- 🎯 Monthly budget tracking with progress alerts
- 📤 CSV export
- 🤖 AI assistant for spending insights

## Tech Stack

- **Frontend:** React Native, Expo, Expo Router
- **Auth:** Clerk
- **Database:** Supabase (Postgres with Row Level Security)
- **AI:** Google Gemini
- **State management:** Zustand
- **Styling:** NativeWind (Tailwind for React Native)

## Getting Started

### Prerequisites
- Node.js 18+
- Expo Go app (for quick testing) or Android Studio / Xcode (for a dev build)
- Accounts on [Clerk](https://clerk.com), [Supabase](https://supabase.com), and [Google AI Studio](https://ai.google.dev)

### Installation

```bash
git clone https://github.com/Strynex7/welth-ai-finance-tracker-project.git
cd welth-ai-finance-tracker-project
npm install
```

### Environment Variables

Create a `.env` file in the project root:

```
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
EXPO_PUBLIC_SUPABASE_KEY=your_supabase_anon_key
EXPO_PUBLIC_GEMINI_API_KEY=your_gemini_key
```

### Run the app

```bash
npx expo start -c
```

Scan the QR code with the Expo Go app, or run on an emulator/simulator.

## License

This project is for educational purposes.

---

*Full setup documentation coming soon.*
=======

>>>>>>> c78f3ae6a19ccd6b4429b4195e29912f295481ac
