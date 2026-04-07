# NewU — Claude Code Context

## Project
Fitness coaching app and platform. iOS app (TestFlight: NewU Coaching). WordPress site at gray-pig-623247.hostingersite.com.

## Tech Stack
- iOS app: React Native or Swift (check repo)
- Backend: API at admin.newu.com.au (DigitalOcean)
- WordPress: Hostinger (gray-pig-623247.hostingersite.com)
- Email: Klaviyo
- Domain: newu.com.au (GoDaddy, parked — needs pointing to Hostinger)

## Target Audience
Men 30-50, fat loss and body transformation, busy professionals

## Brand Voice
Direct, no fluff, results-focused. Speaks to men with busy lives. Short sentences. No em dashes. No corporate language.

## Development Rules
- Always run /review before /ship
- Commit messages: feat/fix/improve/chore prefix
- Brand: keep colours/fonts consistent with NewU design (check design files)
- App is on TestFlight — v3 just released (March 30, 2026)

## Key Commands
- /review — code review
- /ship — commit and push
- /qa — test UI

## Goals
- 100,000 app downloads
- Funnel: SEO blog -> macro calculator -> email capture -> app download -> subscription


## Email Access Rule — CRITICAL

When accessing any Gmail inbox via IMAP:
- ALWAYS use `BODY.PEEK[]` or `BODY.PEEK[HEADER]` — NEVER use `RFC822`
- NEVER mark any email as read
- NEVER call `mail.store(eid, '+FLAGS', '\Seen')`
- Emails must remain in exactly the same read/unread state as before you accessed them
