# 150ml

Personal blog built with [Hugo](https://gohugo.io/) and the [Hextra](https://github.com/imfing/hextra) theme.

## Local Development

Prerequisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Install Hugo module dependencies
hugo mod tidy

# Start local server with live reload
hugo server --logLevel debug --disableFastRender -p 1313
```

## Deployment

The project is hosted on **Netlify**. Every push to `main` triggers a new deploy automatically via `netlify.toml`.

```shell
# Production build (output to ./public)
hugo --gc --minify
```

## Update Theme

```shell
hugo mod get -u
hugo mod tidy
```

## Content Structure

```
content/
├── posts/      # Blog posts  → /posts
├── docs/       # Docs        → /docs
├── about.md    # About page  → /about
└── _index.md   # Homepage
```

### Post front matter

```yaml
---
title: "Post title"
date: 2026-01-01
description: "Short description"
tags:
  - tag1
draft: false
---
```
