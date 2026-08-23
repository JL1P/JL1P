## Juan Luis Almeida Ross

Frontend developer in Miami. I build production web applications in React, Remix, and Vue, with TypeScript.

I spent the last year at a payments infrastructure startup working on the interfaces merchants use to run their payment operations — a pay-by-phone IVR flow end to end, an Apple Pay integration, and the frontend for a role-based access system. The kind of work where a broken form means someone doesn't get paid, so correctness matters more than novelty.

I care about accessibility, performance, and systems that keep working when something upstream fails.

---

### What I'm building

**Name Sprout** — iOS app in React Native and Expo. Every model call goes through a Cloudflare Worker, so no provider credentials ship in the app bundle. Three-provider failover chain so a single outage doesn't take the feature down, with per-user rate limiting and hard spend caps. Guest data merges into the user's account on sign-in through a repository-pattern data layer, deduplicated by content identity. Supabase auth with row-level security.

**Portfolio** — Nuxt 3 and TypeScript, with custom CSS using custom properties as design tokens. No utility framework; I wanted the constraints to be mine.

**PR release notes generator** — Turns GitHub pull requests into release notes. Cloudflare Worker with streaming LLM output.

---

### Working with

TypeScript · React · Remix · Vue 3 · Nuxt 3 · React Native (Expo) · Cloudflare Workers · Supabase · PostgreSQL · Vitest

---

Open to frontend roles in the U.S. — [LinkedIn](https://www.linkedin.com/in/juanluisalmeidaross/)
