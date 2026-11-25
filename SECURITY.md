# Security Policy

## Reporting a vulnerability

Do not disclose suspected vulnerabilities in public Issues. Use the repository host’s private vulnerability-reporting feature when available. If no private channel is configured, contact the repository owner through a private channel shown on their verified profile. No contact address is invented here.

Include the affected area, reproduction conditions, potential impact, and suggested mitigation without including real secrets or unnecessary personal data. Allow reasonable time for triage before public disclosure.

## Secret management

Never commit credentials, tokens, private keys, production data, or populated local environment files. Use ignored local files or an approved secret store. Keep `.env.example` documentation-only. Rotate any exposed secret immediately and remove it from both current content and Git history through a reviewed incident process.

## Current support status

Nexus Commerce is in Planning / Sprint 0 and has no released or operational application version. Security controls described in the documentation are requirements, not implementation claims.
