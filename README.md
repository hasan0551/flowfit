# FlowFit App

FlowFit is a full-stack fitness coaching app with:
- AI-powered video analysis (OpenAI GPT-4o)
- Secure backend proxy for OpenAI
- Magic-link login (Clerk)
- Rate limiting (3 uses/day per user)
- Email alerts for OpenAI usage
- Placeholder shop and chat coach features

## Structure

- `/frontend`: React + TailwindCSS
- `/backend`: Node.js + Express API (OpenAI Proxy)
- `.env.example`: Needed environment variables

## Deployment Instructions

1. Push frontend and backend folders to GitHub (separate repos or one mono-repo).
2. Use Vercel to deploy both.
3. Add env variables from `.env.example`.
4. Set up Clerk auth (https://clerk.com).
5. Configure domain in Vercel and Clerk.

Ask a developer or AI assistant like Claude to help if unsure.
