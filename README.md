# BlogMaker - Next.js Blog Creation Platform

A full-stack SaaS platform that allows users to create and manage their blogs easily.

## Tech Stack

- **Frontend**: Next.js 15 with App Router, React, TypeScript
- **Styling**: Tailwind CSS, Shadcn UI
- **Authentication**: Kinde Auth
- **Database**: PostgreSQL with Prisma ORM
- **Payment Processing**: Stripe
- **Image Storage**: UploadThing
- **Deployment**: Vercel

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# Database
DATABASE_URL="postgresql://..."

# Authentication (Kinde)
KINDE_CLIENT_ID=""
KINDE_CLIENT_SECRET=""
KINDE_ISSUER_URL=""
KINDE_SITE_URL=""
KINDE_POST_LOGOUT_REDIRECT_URL=""
KINDE_POST_LOGIN_REDIRECT_URL=""

# Stripe
STRIPE_SECRET_KEY=""
STRIPE_WEBHOOK_SECRET=""
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=""

# uploadthing
UPLOADTHING_SECRET=""
UPLOADTHING_APP_ID=""
```

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
