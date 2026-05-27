---
solhann_app: true
slug: hello
title: Hello, solhann
description: The first app scaffolded by the create-app skill — proof the whole loop works.
emoji: 👋
---

# 👋 Hello, solhann

The first app scaffolded by the create-app skill — proof the whole loop works.

**Live:** https://hello.solhann.net
**Gallery:** https://create.solhann.net

---

Built on the [solhann.net](https://create.solhann.net) platform. Static site — every push to `main`
auto-deploys via GitHub Actions → rsync → `/var/www/apps/hello/`. The front matter above is what the
gallery reads to render this app's tile, so keep `title` / `description` / `emoji` up to date.
