# ClaudeCheck Web

Free online CLAUDE.md validator. Paste your CLAUDE.md, get instant feedback.

**Live at [claudecheck.pages.dev](https://claudecheck.pages.dev)**

## Features

- 12 validation rules (placeholders, secrets, structure, best practices)
- Runs entirely in your browser — your content never leaves your machine
- Zero dependencies, zero tracking, zero signup

## Rules

| Rule | Severity | What |
|------|----------|------|
| `file-not-empty` | error | File has content |
| `has-title` | error | Has a `# Heading` |
| `no-placeholders` | error | No `[TODO]`, `[Project Name]` leftovers |
| `no-secrets` | error | No API keys or tokens |
| `has-sections` | warning | Multiple sections |
| `heading-hierarchy` | warning | Sequential heading levels |
| `no-empty-sections` | warning | Every section has content |
| `min-length` | warning | Substantial content |
| `has-actionable-content` | info | Contains rules/guidelines |
| `max-length` | info | Under 50K chars |
| `consistent-list-style` | info | Consistent list markers |
| `no-bare-urls` | info | Markdown link syntax |

## Also Available As

- **CLI**: `npx claudecheck` — [repo](https://github.com/lunacompsia-oss/claudecheck)
- **GitHub Action**: `uses: lunacompsia-oss/claudecheck@v1`

## License

MIT
