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

Three pull requests, opened July 2026, currently under review.

**[twentyhq/twenty#23629](https://github.com/twentyhq/twenty/pull/23629)** — editing a Select field on a sorted table view silently discarded the change. Cursor pagination emitted comparison operators the filter predicate did not handle, so it threw and aborted the caller's mutation. SELECT columns are PostgreSQL enums, ordered by option position, which that predicate never receives — so it now declines to answer instead of crashing.

**[doctolib/safe-pg-migrations#178](https://github.com/doctolib/safe-pg-migrations/pull/178)** — `default: false` was read as "no default given", because Ruby treats `!false` the same as `!nil`. The gem fell back to a single unsafe statement, skipping the multi-step path it exists to provide. Regression test included; it fails on main and passes with the fix.

**[SonarSource/sonarqube-mcp-server#510](https://github.com/SonarSource/sonarqube-mcp-server/pull/510)** — a hardcoded 30-second shutdown timeout cut off analyzer downloads on high-latency connections. Now configurable, default unchanged.

All three started by reading the source. In two of them the diagnosis written in the issue turned out to be incomplete.

## Elsewhere

Third place nationally, Hack'Juice cybersecurity hackathon.

Currently building a civic platform with four other developers: NestJS, Next.js, PostgreSQL with Prisma, Docker, Traefik across five VPS, GitLab CI. My share includes porting Supabase `SECURITY DEFINER` RPCs to NestJS services and enforcing append-only audit tables with database triggers, because a convention is only as reliable as the most tired person on a Friday.

## Stack

TypeScript, React, Next.js, Node, NestJS, PostgreSQL, Prisma, Python, Docker.

## Availability

Six-month internship, starting March or April 2027. France, Switzerland, or remote.

simonjspslack@gmail.com · [linkedin.com/in/simon-slack](https://www.linkedin.com/in/simon-slack/)
