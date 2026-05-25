# Poli Page - Feedback

This is the public feedback + issue tracker for **Poli Page**, a platform for authoring PDF templates with HTML, Tailwind CSS, and live preview.

The product code lives in a private monorepo. This repo collects bugs, feature requests, and questions for everything that isn't already in its own public repo: the **editor** (desktop app), the **dashboard** (web), the **documentation** site, and the **website**.

## Quick links

- Found a bug? [Open a bug report](https://github.com/poli-page/feedback/issues/new?template=bug.yml)
- Have an idea? [Request a feature](https://github.com/poli-page/feedback/issues/new?template=feature.yml)
- Got a question? [Start a discussion](https://github.com/poli-page/feedback/discussions/new)
- Need docs? [docs.poli.page](https://docs.poli.page)

## Before you file

- **Search first.** Browse existing [issues](https://github.com/poli-page/feedback/issues?q=is%3Aissue) and [discussions](https://github.com/poli-page/feedback/discussions) - someone may have already raised it.
- **Tell us which product** the issue concerns: editor, dashboard, docs site, or website.
- **For editor bugs**, include the editor version (`Help > About` in the app, or use the in-app "Report a bug" command and the version + OS are auto-injected).
- **For dashboard / website bugs**, mention your browser + OS and ideally a public URL or short screen recording.

## What this repo is NOT

This repo is **not** the place for issues that belong to one of the public packages. Each has its own tracker - filing there gets your report to the right maintainer faster.

**CLI + templates**
- [poli-page/cli](https://github.com/poli-page/cli) - the `poli` command-line tool
- [poli-page/templates](https://github.com/poli-page/templates) - the official templates collection

**SDKs (one per language)**
- [poli-page/sdk-node](https://github.com/poli-page/sdk-node)
- [poli-page/sdk-php](https://github.com/poli-page/sdk-php)
- [poli-page/sdk-python](https://github.com/poli-page/sdk-python)
- [poli-page/sdk-go](https://github.com/poli-page/sdk-go)
- [poli-page/sdk-ruby](https://github.com/poli-page/sdk-ruby)
- [poli-page/sdk-rust](https://github.com/poli-page/sdk-rust)

**Framework integrations** (each consumes the SDK of its host language)
- [poli-page/symfony-bundle](https://github.com/poli-page/symfony-bundle) - Symfony (uses `sdk-php`)
- [poli-page/laravel](https://github.com/poli-page/laravel) - Laravel (uses `sdk-php`)
- [poli-page/django](https://github.com/poli-page/django) - Django (uses `sdk-python`)
- [poli-page/fastapi](https://github.com/poli-page/fastapi) - FastAPI (uses `sdk-python`)
- [poli-page/nestjs](https://github.com/poli-page/nestjs) - NestJS (uses `sdk-node`)
- [poli-page/nextjs](https://github.com/poli-page/nextjs) - Next.js (uses `sdk-node`)

## Support channels

- **Bugs and feature requests** - [Issues](https://github.com/poli-page/feedback/issues) on this repo.
- **Q&A and community** - [Discussions](https://github.com/poli-page/feedback/discussions).
- **Direct (no GitHub account, or private)** - `contact@poli.page`.
