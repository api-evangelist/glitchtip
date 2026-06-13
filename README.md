# GlitchTip

GlitchTip is an open-source error tracking and performance monitoring platform compatible with Sentry SDKs. It captures exceptions, log messages, and Content Security Policy violations in real time, providing performance monitoring for slow requests and database calls, plus uptime monitoring with email and webhook alerts.

## APIs

- **REST API** — Sentry-compatible REST API for managing organizations, projects, teams, issues, and events. Base URL: `https://app.glitchtip.com/api/0/`
- **Event Intake API** — Accepts error and performance events from any Sentry-compatible SDK (Python, JavaScript, Ruby, PHP, Go, Java, and more).
- **MCP Server** — Model Context Protocol server exposing 17 tools for AI assistants to query and act on GlitchTip data.

## Authentication

API access uses scoped auth tokens generated under **Profile > Auth Tokens**. The MCP server uses OAuth 2.0.

## Hosting

- **US**: `https://app.glitchtip.com` (DigitalOcean NYC1)
- **EU**: `https://eu.glitchtip.com` (DigitalOcean FRA1)
- **Self-hosted**: Free; see [installation docs](https://glitchtip.com/documentation/install/)

## Pricing

| Plan | Price | Events/month |
|------|-------|-------------|
| Free | $0 | 1,000 |
| Small | $15/mo | 100,000 |
| Medium | $50/mo | 500,000 |
| Large | $250/mo | 3,000,000 |

Nonprofit and open source discounts start at $5/month.

## Links

- Website: https://glitchtip.com/
- Documentation: https://glitchtip.com/documentation/
- SDK Docs: https://glitchtip.com/sdkdocs/
- Blog: https://glitchtip.com/blog/
- GitLab: https://gitlab.com/glitchtip
- Community (Gitter): https://gitter.im/GlitchTip/community
- Mastodon: https://mastodon.online/@glitchtip
- Contact: sales@glitchtip.com
