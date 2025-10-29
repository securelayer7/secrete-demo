# Secret Scanner Demo Repository

⚠️ **IMPORTANT: This repository contains FAKE credentials for demonstration purposes only!**

## Purpose

This repository is designed to demonstrate GitHub secret scanning tools. All credentials, API keys, and secrets in this repository are **intentionally fake** and non-functional.

## What's Inside

This repo contains examples of common security vulnerabilities:

- **AWS Credentials** - Access keys and secret keys
- **Stripe API Keys** - Payment processing credentials
- **GitHub Personal Access Tokens** - Repository access tokens
- **Database Connection Strings** - PostgreSQL, MySQL, MongoDB URLs
- **Google API Keys** - Cloud service credentials
- **JWT Tokens** - Authentication tokens
- **Private Configuration Files** - `.env`, `config.json`, `secrets.yml`

## Use Cases

This repository is used for:

1. **Security Tool Demonstrations** - Testing secret detection tools
2. **Developer Training** - Learning what NOT to commit to GitHub
3. **CI/CD Pipeline Testing** - Validating security scanning integrations
4. **MCP Server Demos** - Demonstrating AI-powered security tools

## Security Best Practices

**Never commit real secrets to GitHub!** Use:

- Environment variables
- Secret management services (AWS Secrets Manager, HashiCorp Vault)
- `.gitignore` to exclude sensitive files
- Pre-commit hooks to scan for secrets
- GitHub's secret scanning alerts

## Demo at World Wild Web AI & MCP Hack Night

This repository was created for demonstrating a GitHub Secret Scanner built with:
- Model Context Protocol (MCP)
- Cloudflare Workers
- Claude Desktop integration

---

🔒 **Remember:** All secrets in this repo are fake. This is for educational purposes only!
