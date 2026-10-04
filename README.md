# 💰 RupeeWise — AI-Powered Personal Finance Tracker

RupeeWise is a full-stack **AI-powered personal finance management platform** designed to help users track, analyze, and understand their spending.

The platform processes financial information from sources such as **SMS messages and PDF bank statements**, converts the extracted information into structured transaction data, and presents spending insights through interactive dashboards and visualizations.

Built as a **college minor project** using Next.js and modern full-stack technologies.

---

## 🚀 Features

- 📊 Interactive personal finance dashboard
- 💳 Add and manage financial transactions
- 📄 Extract transaction information from PDF bank statements
- 📱 Process financial information from SMS messages
- 🤖 AI-assisted financial data processing
- 🧹 Clean and normalize extracted financial text
- 📈 Interactive graphs and spending visualizations
- 🔐 User authentication and onboarding
- 🗄️ Persistent transaction and user data storage
- 📧 Email-based functionality
- 🛡️ Application security and rate limiting
- 📱 Responsive and modern UI

---

## 🧠 How It Works

RupeeWise follows a pipeline that converts unstructured financial information into useful financial insights.

```text
SMS / PDF Bank Statement
          ↓
    Text Extraction
          ↓
 Financial Information Extraction
          ↓
     Text Cleaning
          ↓
 Transaction Structuring
          ↓
 Database Storage
          ↓
 Spending Analysis
          ↓
 Interactive Graphs & Dashboard
```

<img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">

### Make sure to create a `.env` file with following variables -


DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
# Rupeewise
