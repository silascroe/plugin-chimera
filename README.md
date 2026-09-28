# Plugin Chimera

**Three tools go in. One product crawls out.**

Plugin Chimera is an experimental product breeder. Give it three tools and a mutation level; it generates a micro-product concept, assigns each parent a non-removable role, runs a kill test, and sketches a 48-hour MVP.

The governing rule is simple: **no decorative integrations.** If you can remove one parent and the idea still works, the specimen is invalid.

## Run locally

No build step, package manager, or environment variables are required.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

The site is a static Vercel project. `vercel.json` adds conservative security headers; otherwise Vercel serves the repository root directly.

## What is actually working

- Three arbitrary parent tools
- Mutation pressure from plausible to unlicensed
- Idea-DNA role assignment
- Kill-test dependency check
- 48-hour MVP sketch
- Deterministic specimen IDs
- Shareable URL state
- Parent roulette, because apparently we learned nothing

## Why this exists

A roulette wheel chose **Vercel + Plugin Autopilot + Idea Generator**. This is what survived.
