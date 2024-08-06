# Next.js Course Master

This website is an academy website where you can login with email, gmail or github and create courses, sell courses and buy course from the others.

Test it here: [Course Master](coursemaster-thuannguyen11s-projects.vercel.app)

![Course Master](https://github.com/user-attachments/assets/6e755213-40c2-4956-a7fc-fd563f0ca141)

## Deployment

You can visit the production deployment on Vercel with the following link:

[Course Master](coursemaster-thuannguyen11s-projects.vercel.app)

The technologies used in this project are the following:
- Next.js 14
- Typescript
- Tailwind CSS
- Shadcn/ui
- Clerk for Authentication
- Prisma
- Stripe

## How to run locally:

If you want to run this project locally, follow these steps:

1. Clone the repository

2. Install the dependencies with `npm install`

3. Create a [Clerk](https://clerk.com/) account and get the publishable key and secret key.

4. Create a [Mux](https://dashboard.mux.com/login) account and get token id and token secret.

5. Create a [Uploadthing](https://uploadthing.com/) account and get uploadthing secret and app id.

6. Create a [Stripe](https://stripe.com/) account and get the api key and webhook secret.

7. Create a .env file in the root of the project and add the following environment variables:

| Env Variable | Value |
|------------------|--------------|
| NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY | *Your Clerk client publishable key* |
| CLERK_SECRET_KEY | *Your Clerk secret key* |
| NEXT_PUBLIC_CLERK_SIGN_IN_URL | */sign-in* |
| NEXT_PUBLIC_CLERK_SIGN_UP_URL | */sign-up* |
| DATABASE_URL | *Your database URL to connect* |
| UPLOADTHING_SECRET | *Your Uploadthing secret key* |
| UPLOADTHING_APP_ID | *Your Uploadthing app id* |
| MUX_TOKEN_ID | *Your Mux token id* |
| MUX_TOKEN_SECRET | *Your Mux token secret* |
| STRIPE_API_KEY | *Your Stripe api key* |
| STRIPE_WEBHOOK_SECRET | *Your Stripe webhook secret* |
| NEXT_PUBLIC_BASE_URL | *http://localhost:3000* |

8. Run the project with `npm run dev` or `npm run build` and `npm run start`
