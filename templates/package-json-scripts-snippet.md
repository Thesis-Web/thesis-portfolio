
## Suggested `package.json` scripts (copy/paste)

Add these to each Node repo (adjust commands as needed):

```json
{
  "scripts": {
    "format": "prettier . --write",
    "format:check": "prettier . --check",
    "lint": "eslint .",
    "typecheck": "tsc -p tsconfig.json --noEmit",
    "build": "npm run typecheck && <your-build-command>"
  }
}
```

Notes:
- If a repo doesn’t use ESLint, keep `format`/`format:check` and omit `lint`.
- Keep CI compatible with `--if-present` for build/typecheck if a repo is docs-only.
