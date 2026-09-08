# Contributing to Resizes

Thanks for your interest. We welcome improvements to public tooling, docs, and community content.

## What we build

| Product | What it does |
| --- | --- |
| **[Resizes Agentic](https://resiz.es)** | Engineering agents for cloud ops — read-only by default, with human approval for proposed actions |
| **[Resizes Platform](https://resiz.es/services)** | Managed Internal Developer Platforms on your cloud |
| **[Resizes AI](https://resizes.ai)** | Business agents SaaS |

Most product and customer repos are private. Public contribution surfaces today:

- [`github-actions`](https://github.com/resizes/github-actions) — reusable GitHub Actions and workflows
- [`platform-terraform-module-github-oidc-aws-role`](https://github.com/resizes/platform-terraform-module-github-oidc-aws-role) — Terraform module for GitHub OIDC → AWS IAM
- [`blog`](https://github.com/resizes/blog) — [blog.resiz.es](https://blog.resiz.es)

## Getting started

1. Fork the repository you want to change.
2. Create a focused branch:
   ```bash
   git checkout -b feat/my-improvement
   ```
3. Make the change. Update tests and docs when they apply.
4. Open a pull request using the template.

## Code style

- Keep PRs small and focused.
- Prefer [Conventional Commits](https://www.conventionalcommits.org/).
- Add or update documentation when behaviour changes.

## Community

- Be respectful and inclusive (see [Code of Conduct](./CODE_OF_CONDUCT.md)).
- Questions and discussion: [Discord](https://discord.gg/kC25JjyyKD).
- Security reports: see [SECURITY.md](./SECURITY.md) — do not open a public issue.
