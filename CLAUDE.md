# CLAUDE.md — {{PROJECT_NAME}}

**Read this first. Every time. Before touching anything.**

---

## What This Is

{{2-3 sentence description of the project.}}

Live at: {{URL}}

---

## Stack

- **Framework**: {{Next.js 16 / React 19}}
- **Language**: TypeScript 5.x strict
- **Styling**: {{Custom CSS / Tailwind v4}}
- **State**: {{Zustand / Redux}}
- **Testing**: {{Vitest / Playwright}}
- **Deploy**: {{Render / Vercel}}

Run: `npm run dev` | Build: `npm run build` | Test: `npm run test`

---

## Design System (STRICT)

**Tokens:**
```css
--bg: #000
--fg: #fff
--muted: rgba(255,255,255,.55)
--border: rgba(255,255,255,.15)
--surface: rgba(255,255,255,.04)
--accent: #ff6600
--font-mono: 'Berkeley Mono', monospace
```

**Hard rules:**
1. NO inline styles with static values
2. NO magic numbers — use CSS vars
3. Max file size: 150 lines — split if exceeded
4. One component per file
5. ALL UI labels UPPERCASE with letter-spacing
6. 150ms ease-out for all transitions
7. NO box-shadow, NO gradients

---

## Current Status

| Phase | Status | Notes |
|-------|--------|-------|
| 1. Foundation | {{🟡 In Progress}} | {{Brief note}} |
| 2. Core Features | ⚪ Not Started | |
| 3. UI Polish | ⚪ Not Started | |
| 4. Production | ⚪ Not Started | |

**Active Work:**
- {{What you're doing now}}

---

## Critical Decisions

### {{Date}}: {{Decision}}
**What**: {{Description}}
**Why**: {{Rationale}}

---

## Anti-Patterns (NEVER DO)

1. **{{Name}}**: {{What}} → {{Why not}} → {{Instead}}

---

## Session Rituals

1. Start here — This file loads automatically
2. Check docs/STATUS.md for progress
3. Update when completing phases
4. Log decisions in docs/DECISIONS.md

---

## Contact

- **Owner**: {{Name}}
- **Last Updated**: {{Date}}
