# Hook: Pre-Commit

## Checks

1. Type Check
   ```bash
   npm run typecheck
   ```

2. Lint
   ```bash
   npm run lint
   ```

3. Quick Test
   ```bash
   npm run test:quick
   ```

## Config

Add to package.json:
```json
{
  "husky": {
    "hooks": {
      "pre-commit": "npm run typecheck && npm run lint"
    }
  }
}
```
