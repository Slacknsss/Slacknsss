# Simon Slack

Second-year software engineering student at Epitech Paris, graduating 2028.
QA Analyst at Anybuddy, a court-booking platform with around 500,000 users.

My job is finding what breaks before users do. My own projects are the ones I have to keep running afterwards.

## Running in production

**[3venmade.com](https://3venmade.com)** — clothing brand storefront. Built and operated alone.
Next.js, TypeScript, Prisma on PostgreSQL, Stripe Checkout with idempotent webhooks, admin back-office, row-level security. It takes real orders and real money.

**[vibaura.app](https://vibaura.app)** — Elo rating engine for padel. Algorithm and data model written from scratch, not pulled from a library.

**[slacklaboratory.com](https://slacklaboratory.com)** — portfolio.

## Open source

**[doctolib/safe-pg-migrations#178](https://github.com/doctolib/safe-pg-migrations/pull/178)** — the gem exists to turn a dangerous `ALTER TABLE` into a safe multi-step migration. It skipped that path entirely for `default: false`, emitting a single `ADD COLUMN ... DEFAULT FALSE NOT NULL` on a live table. The guard tested `!default`, and Ruby treats `!false` exactly like `!nil`, so a legitimate boolean default was read as "no default given". One line, plus a regression test that fails without the fix and passes with it. Under review, July 2026.

## Elsewhere

Third place nationally, Hack'Juice cybersecurity hackathon.

Currently building a civic platform with four other developers: NestJS, Next.js, PostgreSQL with Prisma, Docker, Traefik across five VPS, GitLab CI. My share includes porting Supabase `SECURITY DEFINER` RPCs to NestJS services and enforcing append-only audit tables with database triggers, because a convention is only as reliable as the most tired person on a Friday.

## Stack

TypeScript, React, Next.js, Node, NestJS, PostgreSQL, Prisma, Python, Docker.

## Availability

Six-month internship, starting March or April 2027. France, Switzerland, or remote.

simonjspslack@gmail.com · [linkedin.com/in/simon-slack](https://www.linkedin.com/in/simon-slack/)
