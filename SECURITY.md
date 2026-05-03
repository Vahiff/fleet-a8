# Security Policy

## Supported Versions

The active `main` branch is the only supported development line unless release branches are created later.

## Reporting A Vulnerability

Do not open public issues for secrets, authentication bugs, payment bugs, data leaks, unsafe WebView behavior, or anything that could put users at risk.

Report security concerns privately to the repository owner with:

- affected repository and branch
- steps to reproduce
- expected and actual result
- screenshots or logs if safe to share
- suggested fix if known

## Security Rules

- Never commit signing keys, keystores, passwords, API keys, or payment secrets.
- Keep release signing files outside Git.
- Review Android permissions before release.
- Keep WebView behavior restrictive and intentional.
- Treat user data as private by default.
