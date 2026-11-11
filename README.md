# Cloudflare Deploy

A deployment and platform guidance skill for publishing applications and infrastructure with Cloudflare.

## Platform areas

- Workers and Pages for edge functions and web applications.
- Durable Objects, Workflows, and Containers for stateful or background workloads.
- D1, R2, KV, Queues, Vectorize, and other storage and data services.
- AI, networking, tunnels, media, and security products.
- Wrangler authentication, configuration, deployment, and troubleshooting.

## Usage

Use this skill when deploying, hosting, publishing, or configuring a project on Cloudflare. Follow the product decision trees in `SKILL.md`, then consult the matching detailed reference under `references/`.

Before deployment, verify the active Cloudflare account with Wrangler and confirm the target account, project, environment, and deployment scope. Use a least-privilege API token in CI/CD and never commit credentials.
