# Security Policy

## Safety Philosophy

AUTOBOT is designed with a "do no harm" principle. It will:
- Never execute arbitrary code
- Never modify test assertions to hide failures
- Never change public API signatures silently
- Skip any fix it's not confident about
- Only make atomic, reversible changes

## Reporting a Vulnerability

If you discover a security issue in AUTOBOT's skill instructions that could cause harmful behavior:

1. **Do NOT** open a public issue
2. Email the maintainers or use GitHub's private vulnerability reporting
3. Describe the issue and potential impact
4. Allow reasonable time for a fix before public disclosure

## Scope

Since AUTOBOT is an AI agent skill (markdown instructions), security concerns primarily involve:
- Instructions that could lead to destructive file operations
- Logic that could bypass safety guardrails
- Patterns that could expose sensitive data

We take all reports seriously and will respond promptly.