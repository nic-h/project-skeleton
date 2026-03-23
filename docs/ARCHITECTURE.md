# Architecture

## Overview

{{High-level description}}

```
Frontend → API → Data
```

## Stack

- **Framework**: {{Next.js / React}}
- **State**: {{Zustand}}
- **Data**: {{SQLite / Postgres}}

## Directory Structure

```
src/
  app/              # Routes
  components/
    ui/             # Primitives
    features/       # Feature components
  hooks/            # Custom hooks
  services/         # API calls
  stores/           # State
  types/            # TypeScript
  utils/            # Logic
```

## Key Decisions

### {{Decision}}
**What**: {{Description}}
**Why**: {{Rationale}}
