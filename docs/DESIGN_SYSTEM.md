# Design System

## Philosophy

{{Aesthetic description}}

## Tokens

```css
:root {
  --bg: #000;
  --fg: #fff;
  --muted: rgba(255,255,255,.55);
  --border: rgba(255,255,255,.15);
  --surface: rgba(255,255,255,.04);
  --accent: #ff6600;
  --font-mono: 'Berkeley Mono', monospace;
}
```

## Hard Rules

1. NO inline styles
2. NO magic numbers
3. Max 150 lines per file
4. One component per file
5. UPPERCASE labels
6. 150ms ease-out transitions
7. NO box-shadow
8. NO gradients
