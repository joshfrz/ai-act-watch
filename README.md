# AI Act Watch (MVP)

This is a minimal Next.js site for AI Act Watch. It includes:
- Landing page
- Privacy Policy
- Terms of Service

## Quick Start (Local)
```bash
npm install
npm run dev
```
Visit http://localhost:3000

## Deploy to Vercel
1) Create a Vercel account and click **New Project**.
2) Import this repo from GitHub.
3) In Project → Settings → Domains, add `aiactwatch.com`.
4) Make sure your DNS has:
   - A @ -> 76.76.21.21
   - CNAME www -> cname.vercel-dns.com
5) Redeploy. Your site should be live at https://aiactwatch.com

## Next Steps
- Wire the email form to Mailchimp.
- Add Stripe checkout.
- Add scraper + summarizer backend (separate service) and connect to a dashboard.
