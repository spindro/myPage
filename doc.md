# doc.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

A personal academic website for Indro Spinelli, built with [Hugo](https://gohugo.io/) (v0.111.3 extended). It deploys to GitHub Pages at `https://spindro.github.io/` via a git subtree setup where `public/` is its own git repo tracking the `spindro.github.io` repository.

## Commands

```bash
hugo server          # Local dev server with live reload at http://localhost:1313
hugo                 # Build to public/
./deploy.sh          # Build + commit + push public/ to GitHub Pages
./deploy.sh "msg"    # Same with a custom commit message
```

There are no tests, linters, or package managers.

## Architecture

**Layout system** — `layouts/_default/baseof.html` is the single base template. Pages inject content into `{{ block "main" . }}`. Two container widths are used: `.home-container` (max 1400px, for the homepage split layout) and `.inner` (max 768px, for all other pages).

**Homepage** — `content/_index.md` uses `layout: landing_page`, which renders `layouts/landing_page.html`. That template creates a two-column flex layout: left column contains the bio text plus an embedded render of `content/news.md`, right column holds the profile image (`static/img/pp.jpeg`). The news content is pulled in with `site.GetPage "page" "news.md"` and displayed as a glass card.

**SCSS pipeline** — `assets/theme.scss` is the single compiled stylesheet (processed by Hugo Pipes + fingerprinted). `assets/main.scss` and the other partial SCSS files in `assets/` are **not** imported anywhere and appear to be legacy/unused. All active styles live in `theme.scss`.

**Theme variables** — Colors and fonts are hardcoded as SCSS variables at the top of `theme.scss` (not read from `config.toml` at build time). When changing theme colors or fonts, update `theme.scss` directly, not just `config.toml`.

**Visual style** — The site uses a "light neon glass" aesthetic: glassmorphism nav pill, iridescent blue-to-purple gradient accents (`#3B82F6` → `#8B5CF6`), CSS entry animations, and a fixed radial gradient mesh background.

**News format** — Each news item in `content/news.md` is a paragraph with a `**Mon YYYY**` bold date followed by a `<span>` for the text. The CSS in `theme.scss` styles `.landing-page-news p` as a flex row to align dates and content.

**Deployment** — `public/` has its own `.git` pointing to the GitHub Pages repo. `deploy.sh` builds Hugo, `cd`s into `public/`, commits everything, and pushes to `origin master`. The source repo (this one) is separate and must be committed/pushed independently.
