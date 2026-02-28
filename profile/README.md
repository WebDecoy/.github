<p align="center">
  <a href="https://webdecoy.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://webdecoy.com/assets/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://webdecoy.com/assets/logo-light.svg">
      <img alt="Web Decoy" src="https://webdecoy.com/assets/logo-dark.svg" height="60">
    </picture>
  </a>
</p>

<p align="center">
  <strong>Bot detection and remediation for the AI era.</strong><br>
  Passive honeypots, behavioral analysis, and vision AI CAPTCHA to stop scrapers and sophisticated bots.
</p>

<p align="center">
  <a href="https://webdecoy.com">Website</a> &middot;
  <a href="https://webdecoy.com/product/fcaptcha-demo/">Live Demo</a> &middot;
  <a href="https://www.npmjs.com/package/@webdecoy/node">npm</a>
</p>

---

### Open Source Projects

| | Project | What it does |
|---|---------|-------------|
| **[FCaptcha](https://github.com/WebDecoy/FCaptcha)** | Self-hosted CAPTCHA | Detects bots, vision AI agents, and headless browsers through 40+ behavioral signals and SHA-256 proof of work. Go, Python, and Node.js servers. Privacy-first, no external dependencies. |
| **[Node SDK](https://github.com/WebDecoy/node-sdk)** | Bot detection middleware | TLS fingerprinting (JA3/JA4), rate limiting, and rules engine for Express, Fastify, and Next.js. Two-tier analysis with fail-open design. |

### What We're Building

Web Decoy is a platform for detecting and responding to automated threats — from basic scrapers to AI-powered agents that use vision models to navigate sites like humans do.

- **Decoy links** — invisible honeypot traps that catch bots ignoring `robots.txt`, including GPTBot, ClaudeBot, and 20+ AI crawlers
- **Endpoint decoys** — API honeypots that catch credential stuffing, injection attacks, and path enumeration with zero false positives
- **Behavioral analysis** — TLS fingerprinting, mouse entropy, keystroke cadence, and timezone consistency checks
- **Vision AI detection** — purpose-built to detect screenshot-and-click automation (Claude Computer Use, OpenAI Operator, and similar)
- **Response automation** — integrates with Cloudflare, AWS WAF, and custom webhooks for real-time blocking

### Quick Start

**FCaptcha** — one command:

```bash
docker run -d -p 3000:3000 -e FCAPTCHA_SECRET=my-secret ghcr.io/webdecoy/fcaptcha
```

**Node SDK** — add to any Express app:

```bash
npm install @webdecoy/express
```

```typescript
import { webdecoy } from '@webdecoy/express';

app.use(webdecoy({
  apiKey: process.env.WEBDECOY_API_KEY,
  threatScoreThreshold: 70,
}));
```

### Contributing

FCaptcha and the Node SDK are MIT-licensed. Issues and PRs welcome.
