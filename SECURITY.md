# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any OpenStacks repository, please report it responsibly.

**Do not open a public issue.** Instead, contact [Varna Sri Raman](https://on-web.link/varna) directly with:

1. The repository and file(s) affected
2. A description of the vulnerability
3. Steps to reproduce, if applicable

You should receive a response within 7 days. We will work with you to understand the issue and coordinate a fix before any public disclosure.

## Scope

This policy covers all repositories in the OpenStacks ecosystem:

- OpenStacks-for-Change (hub)
- InsightStack, FieldStack, EquityStack, SignalStack
- RootStack, BridgeStack, ViewStack, PolicyStack

## What We Consider Security Issues

- Exposure of sensitive data (API keys, credentials, PII)
- SQL injection or command injection vulnerabilities
- Path traversal or file access issues
- Dependencies with known critical vulnerabilities

## Data Sensitivity

OpenStacks tools are designed for development sector work that may involve data about vulnerable populations. While repositories contain only synthetic sample data, contributors should be especially careful never to commit real respondent data, even if anonymised.
