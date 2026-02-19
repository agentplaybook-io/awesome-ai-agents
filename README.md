# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources for deploying and managing self-hosted AI agents.

## Contents

- [Frameworks](#frameworks)
- [Deployment Guides](#deployment-guides)
- [Hosting Options](#hosting-options)
- [Skills & Integrations](#skills--integrations)
- [Security](#security)
- [Communities](#communities)

## Frameworks

| Framework | Stars | Description |
|-----------|-------|-------------|
| [OpenClaw](https://github.com/openclaw/openclaw) | 68k+ | Autonomous AI agent with MCP support |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 160k+ | Autonomous GPT-4 agent |
| [LangChain](https://github.com/langchain-ai/langchain) | 80k+ | LLM application framework |
| [CrewAI](https://github.com/joaomdmoura/crewAI) | 15k+ | Multi-agent orchestration |

## Deployment Guides

### Free / $5 per month
- [Cloudflare Workers + Moltworker](https://agentplaybook.io) — Run OpenClaw for $5/mo
- Vercel Edge Functions
- Fly.io free tier

### Self-Hosted
- [Mac Mini 24/7 Setup](https://agentplaybook.io) — Dedicated hardware guide
- [VPS with Ansible](https://agentplaybook.io) — Automated deployment
- Docker Compose templates

### Enterprise
- AWS ECS / EKS
- Google Cloud Run
- Azure Container Apps

## Hosting Options

| Option | Cost | Latency | Best For |
|--------|------|---------|----------|
| Cloudflare Workers | $5/mo | Low | Personal agents |
| VPS (Hetzner/Hostinger) | $5-20/mo | Medium | Full control |
| Mac Mini | $500 one-time | Lowest | 24/7 local agent |
| Cloud Functions | Pay-per-use | Variable | Burst workloads |

## Security

- [Security Hardening Guide](https://agentplaybook.io) — Production-ready security
- Never expose admin panels publicly
- Use allowlists for Telegram/Discord DMs
- Rotate API keys regularly
- Sandbox skill execution

## Step-by-Step Playbooks

For detailed, copy-paste deployment guides:

**[Agent Playbook →](https://agentplaybook.io)**

- Cloudflare Moltworker Setup
- Ansible VPS Deployment
- WhatsApp/Telegram Bot Integration
- Security Hardening
- Multi-Channel Setup

## Communities

- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA)
- [r/selfhosted](https://reddit.com/r/selfhosted)
- OpenClaw Discord

## Contributing

PRs welcome. Add resources via pull request.

## License

CC0 — Public domain
