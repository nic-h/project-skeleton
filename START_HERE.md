# 🚀 Hermes Project Skeleton

Canonical repo template for AI-assisted development.

## What This Is

Synthesized from best patterns across nic-h and nnebula0 repos:
- nokyc.money — Design law enforcement
- deepscrape — Agent/command structure
- SSW-SKU-FIT — Documentation system
- SSW_IMG_QA — Implementation rules
- SSW_AUTO_RNDR — Domain continuity

## How to Use

1. **Fill in placeholders** — Replace all {{PLACEHOLDER}} values
2. **Start with CLAUDE.md** — This is the master context file
3. **Remove this file** — After setup: `rm START_HERE.md`

## Structure

```
├── CLAUDE.md              ← Master AI context (READ FIRST)
├── README.md              ← Entry point
├── .claude/               ← Agent system
│   ├── agents/            ← Specialist AI roles
│   ├── commands/          ← Reusable operations
│   ├── hooks/             ← Lifecycle automation
│   └── skills/            ← Project behaviors
└── docs/                  ← Documentation
    ├── ARCHITECTURE.md
    ├── DESIGN_SYSTEM.md
    ├── FUNCTIONAL_SPEC.md
    ├── RUNBOOK.md
    ├── HANDOVER.md
    ├── DECISIONS.md
    └── STATUS.md
```

## Next Steps

1. Edit `CLAUDE.md` — Add project name, stack, design system
2. Edit `docs/` — Fill in architecture, spec, design system
3. Customize `.claude/` — Adjust agents/commands as needed
4. Start building

## Key Principles

1. CLAUDE.md is living truth — Update constantly
2. Docs separate concerns — Don't overload one file
3. Agents provide focus — Use specialized roles
4. Commands standardize — Repeatable operations
5. Hard rules enforced — Design tokens or death
