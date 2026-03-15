# ai-webhook

[![npm version](https://img.shields.io/npm/v/ai-webhook.svg)](https://www.npmjs.com/package/ai-webhook)
[![npm downloads](https://img.shields.io/npm/dm/ai-webhook.svg)](https://www.npmjs.com/package/ai-webhook)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-webhook)](https://github.com/lxgic-studios/ai-webhook/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate production-ready webhook handlers with signature verification, retry logic, and idempotency. Just describe the event.

## Install

```bash
npm install -g ai-webhook
```

## Usage

```bash
npx ai-webhook "stripe payment succeeded"
# Generates Express webhook handler with retry logic

npx ai-webhook "github push event" -f nextjs
# Next.js API route handler

npx ai-webhook "shopify order created" -o webhook-handler.ts
# Save to file
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-f, --framework <name>` - Framework: express, fastify, nextjs (default: express)
- `-o, --output <path>` - Save to file

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
