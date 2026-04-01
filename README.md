# Smart Contact Manager 🚀

> Never lose a great connection again.

A full-stack AI-powered contact relationship management app built with **Next.js 14**, **Convex**, **Clerk**, and **Claude AI**. Track your professional network, get intelligent follow-up suggestions, and maintain strong relationships with AI-powered insights.

## ✨ Features

### 🎯 Core Features
- **Relationship Intelligence Score** (0-100) - AI-powered scoring based on interaction frequency, recency, and channel quality
- **Smart Follow-Up Engine** - Never forget to reconnect with automated, intelligent reminders
- **AI Contact Assistant** - Chat with Claude to get insights, draft emails, and discover opportunities
- **Auto-Tagging** - Automatically categorize contacts (recruiters, clients, investors, friends)
- **Lifecycle Management** - Track contact stages (new, active, dormant, archived)
- **Smart Deduplication** - Detect and merge duplicate contacts with fuzzy matching
- **Context Memory** - AI-summarized notes for every interaction
- **Natural Language Search** - Find contacts with queries like "recruiters from fintech I haven't contacted in 60 days"
- **Analytics Dashboard** - Visualize network growth, relationship distribution, and engagement

### 🎨 Design
- **Yellow/Black Color Palette** - Professional dark theme with accent colors (#F5B301, #FED053)
- **Responsive UI** - Works seamlessly on desktop and mobile
- **Smooth Animations** - Framer Motion for delightful interactions
- **Beautiful Charts** - Recharts for data visualization

## 🛠️ Tech Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, Tailwind CSS
- **Backend**: Convex (Database, Queries, Mutations, Actions)
- **Authentication**: Clerk (Email + OAuth)
- **AI**: Claude 3.5 Sonnet (Chat, Summarization, NLP)
- **Charts**: Recharts
- **Icons**: Lucide React
- **Animations**: Framer Motion

## 📦 Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd smartcontactmanager
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**

Create a `.env.local` file in the root directory:

```bash
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Convex Backend
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url

# Claude AI
ANTHROPIC_API_KEY=your_anthropic_api_key
```

4. **Set up Convex**
```bash
npx convex dev
```

This will:
- Initialize your Convex project
- Push your schema to the backend
- Start the Convex development server

5. **Run the development server**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see your app!

## 🚀 Quick Start

The app is ready to run! Just make sure you have:
1. ✅ Clerk account and API keys configured
2. ✅ Convex project set up (`npx convex dev`)
3. ✅ Claude API key from Anthropic

Then run `npm run dev` and start building your network!

---

**Built with ❤️ for hackathons and recruiters**


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
