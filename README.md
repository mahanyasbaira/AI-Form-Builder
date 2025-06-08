# 🧠 AI Form Builder

An AI-powered form generation platform that lets users effortlessly create, publish, and manage forms using natural language prompts.

![AI Form Builder Screenshot](./public/screenshot.png) <!-- Replace with actual path -->

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) with App Router
- **UI Components**: [ShadCN UI](https://ui.shadcn.com/)
- **Authentication**: [NextAuth.js](https://next-auth.js.org/)
- **AI Integration**: [OpenAI API](https://openai.com/)
- **ORM**: [Drizzle ORM](https://orm.drizzle.team/)
- **Database**: PostgreSQL
- **Payments**: [Stripe](https://stripe.com/)
- **Data Tables**: [TanStack Table](https://tanstack.com/table)
- **Schema Validation**: [Zod](https://zod.dev/)
- **Type Checking**: TypeScript
- **Analytics**: [Plausible Analytics](https://plausible.io/)
- **Deployment**: [Vercel](https://vercel.com/)

## ✨ Features

- ✅ **Authentication**
- ✅ **AI Form Generation**
- ✅ **Form Publishing & Submissions**
- ✅ **View & Manage Your Forms**
- ✅ **Admin Panel**
- ✅ **View Form Results**
- ✅ **User Settings & Subscription Upgrades**
- ✅ **Built-in Analytics**
- ✅ **Landing Page**
- ❌ **Form Editing** (Coming soon — PRs welcome!)

## 🚀 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/ai-form-builder.git](https://github.com/mahanyasbaira/AI-Form-Builder.git
cd ai-form-builder

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
# or
bun install


Start the development server:
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev


Open http://localhost:3000 in your browser.

🧪 Environment Variables

Create a .env file in the root directory and add the following variables:
# OpenAI API
OPENAI_API_KEY="your-openai-key"

# Google Auth (NextAuth)
GOOGLE_CLIENT_ID="your-google-client-id"
GOOGLE_CLIENT_SECRET="your-google-client-secret"

# Auth secret (NextAuth)
AUTH_SECRET="your-secret"

# PostgreSQL database
DATABASE_URL="postgresql://user:password@host:port/dbname"

# Stripe
NEXT_PUBLIC_PUBLISHABLE_KEY="your-stripe-pk"
STRIPE_SECRET_KEY="your-stripe-sk"
STRIPE_WEBHOOK_SECRET="your-stripe-webhook-secret"
STRIPE_WEBHOOK_LOCAL_SERCRET="your-stripe-local-webhook-secret"

# Analytics
PLAUSIBLE_DOMAIN="yourdomain.com"

⚠️ Never commit your .env file or any credentials to version control.

📁 Important Paths
	•	app/page.tsx – Home / Landing Page
	•	app/api/ – API Routes (including OpenAI integration)
	•	app/dashboard/ – Authenticated user dashboard
	•	lib/ – Helper functions, OpenAI client, DB
	•	components/ – Reusable UI elements

🌐 Deployment

This project is ready to deploy on Vercel. Simply connect the repo and add your .env variables in the Vercel dashboard.

🤝 Contributing

Contributions are welcome! Especially for:
	•	🛠 Form Editing support
	•	🎨 UI/UX improvements
	•	🧪 Test coverage

Fork the repo → Create a new branch → Submit a pull request.

