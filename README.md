# 🤖 AUTOBOT

**Self-healing code agent skill** — like an immune system for your codebase.

AUTOBOT autonomously scans, diagnoses, and fixes code health issues: bugs, bad design, code smells, dead code, and structural problems. It applies minimal, safe fixes and reports what it found.

## Installation

```bash
npx skills add YOUR-USERNAME/autobot
```

## Usage

Trigger AUTOBOT with phrases like:

- "Run AUTOBOT on this codebase"
- "Health check this project"
- "Find and fix code issues"
- "Self-heal this code"

## Safety Guarantees

- ✅ **Do no harm** — only fixes what is clearly broken or objectively bad
- ✅ **Never modifies tests** to make them pass
- ✅ **Never changes public APIs** without flagging
- ✅ **Atomic fixes** — each change is small and reversible
- ✅ **Runs existing tests** after fixes to verify nothing broke
- ✅ **Skips uncertain fixes** — reports them for human decision

## How It Works

1. **Scan** — Reads codebase structure and identifies languages/frameworks
2. **Diagnose** — Categorizes issues by severity (critical bugs → design → smells → style)
3. **Fix** — Applies minimal safe changes from highest to lowest severity
4. **Report** — Outputs a health report with all findings and actions taken

## License

[MIT](LICENSE)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Security

See [SECURITY.md](SECURITY.md) for reporting vulnerabilities.