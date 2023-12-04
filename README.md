# SprintEase

This is `SprintEase` a B2B SaaS (Business to Business Software as a Service) Flexible work management tool for agile development

#### Landing page

<img src="/demo-images/app-boards.PNG"/>
<img src="/demo-images/board.PNG"/>
<img src="/demo-images/task-info.PNG"/>

##

#### Platform

##

## Stack

`React, Typescript, Next.js 14, Clerk, Supabase, PostgreSQL, Zustand, Prisma, Zod, Tailwind, Shadcn-ui, Server Actions, Stripe, sonner`

### Prerequisites

**Node version 18.x.x**

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_WEBHOOK_SECRET=
```

### Additional info

This application is built with `Server Actions`

### Setup Prisma

Add PostgreSQL Database

```bash
npx prisma generate
npx prisma db push

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
