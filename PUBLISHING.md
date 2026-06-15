# Publishing

This directory is already a local git repository on branch `main`.

## Current Local State

- Repository name: `learn-xx-prompt`
- Initial commit: created locally
- Remote: not configured yet

## Option A: Publish With GitHub UI

1. Create a new empty repository on GitHub named `learn-xx-prompt`.
2. Choose visibility: public or private.
3. Do not initialize it with README, license, or `.gitignore`; this project already has them.
4. Add the remote and push:

```bash
git remote add origin git@github.com:<owner>/learn-xx-prompt.git
git push -u origin main
```

If using HTTPS:

```bash
git remote add origin https://github.com/<owner>/learn-xx-prompt.git
git push -u origin main
```

## Option B: Publish With GitHub CLI

If `gh` is installed and authenticated:

```bash
gh repo create <owner>/learn-xx-prompt --public --source=. --remote=origin --push
```

Use `--private` instead of `--public` for a private repo.

## GitHub Pages

This project is Markdown-first and can be published as GitHub Pages later. A simple next step is to enable Pages from the repository settings and choose the `main` branch as the source.

## What To Confirm Before Publishing

- GitHub owner or organization
- Public or private visibility
- Whether GitHub Pages should be enabled
- Whether the repository should keep the name `learn-xx-prompt` or use a clearer name such as `learn-agent-prompt`
