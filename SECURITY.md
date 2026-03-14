# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly:

1. **Do NOT open a public issue**
2. Open a [GitHub Security Advisory](https://github.com/AgriciDaniel/linkedin-content-creator/security/advisories/new) on this repo
3. Or contact the maintainer directly

## Response Timeline

- **Acknowledgment**: Within 72 hours of report
- **Assessment**: Within 7 days with initial assessment

## Supported Versions

Only the latest version receives security updates.

## Security Practices

- OAuth tokens are stored client-side only and never committed to the repository
- API keys should be configured via environment variables, not hardcoded
- The `.env` file is gitignored to prevent accidental credential exposure
