# Yadegar & Co — Project Overview

## What This Is
A client intake form and CRM for Yadegar & Co, a high-end bespoke watchmaker (Est. 2020). Clients apply for a 1-on-1 session with the watchmaker. No catalog, fully custom pieces only.

## Live URLs
- **Intake form:** https://yadegar-co.com
- **Admin CRM:** https://yadegar-co.com/admin.html (password: iloveronel)
- **Netlify dashboard:** https://funny-cat-bf294c.netlify.app

## Tech Stack
- **Frontend:** Vanilla HTML/CSS/JS (index.html + admin.html)
- **Database:** Supabase (stores all form submissions)
- **Hosting:** Netlify (auto-deploys from GitHub on every push)
- **Domain:** GoDaddy → yadegar-co.com (nameservers pointed to Netlify)
- **Repo:** https://github.com/yosephyadegar92-a11y/yadegar-.git

## Files
- `index.html` — the client intake form (4 steps, budget filter, Supabase submit)
- `admin.html` — private CRM dashboard (password protected, loads from Supabase)
- `config.js` — Supabase URL and anon key
- `logo.jpeg` — brand logo (white text on black, mix-blend-mode: screen)
- `CLAUDE.md` — this file

## Supabase
- **URL:** https://kdivctpemgrvrsagypbm.supabase.co
- **Table:** applications
- **Columns:** id, created_at, status, notes, first_name, last_name, email, phone, city, state, purpose, vision, refs, budget, source, timeline, extra

## Design
- Black background (#050505), white text (#ffffff)
- Fonts: Cinzel (headings), Cormorant Garamond (italic subtext), Inter (body)
- Mobile-first (primary users come from Instagram bio link)
- Logo centered on all screens using mix-blend-mode: screen

## How to Deploy Changes
```
git add .
git commit -m "your message"
git push
```
Netlify auto-deploys within 30 seconds.

## Owner
- Email: yosephyadegar92@gmail.com
- Instagram drives all traffic to the intake form via bio link
