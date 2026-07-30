# GitHub Publishing Guide

## Recommended repository settings

- Repository name: `project-apollo`
- Description: `Secure mobile command environment for a Galaxy S25 and Galaxy Tab S11, featuring governed NetWatch v2.0 access, device modes, recovery planning, and a unified visual identity.`
- Visibility: public only after the sanitization review; otherwise private.
- Default branch: `main`
- Topics: `android`, `samsung`, `mobile-security`, `homelab`, `network-monitoring`, `documentation`, `cybersecurity-portfolio`
- Enable: issues, secret scanning, push protection, and dependency/security alerts where available.
- Disable: wiki and projects unless they will be actively maintained.

## Pre-publish gate

- [ ] Search all files for real names, addresses, URLs, hostnames, IP addresses, identifiers, tokens, and secrets.
- [ ] Confirm no raw screenshots, backups, diagnostics, or local configuration are tracked.
- [ ] Review every image at full resolution and remove metadata.
- [ ] Confirm artwork ownership or permission.
- [ ] Check Markdown links and repository tree.
- [ ] Confirm the selected visibility.
- [ ] Review the staged diff before committing.

## Recommended initial commit

Commit message:

```text
docs: establish Project Apollo mobile command environment
```

Commit description:

```text
Create the GitHub-ready Project Apollo documentation baseline for the
Galaxy S25 and Galaxy Tab S11.

- define distinct phone and tablet roles and operating modes
- establish security, privacy, application, sync, and recovery standards
- design one-action NetWatch v2.0 access for the tablet
- add device build, monthly review, and lost-device checklists
- codify the shared Hermes, Hydra, and Apollo visual identity
- provide sanitized portfolio and asset-publishing guidance
```

## Suggested first release

- Tag: `v1.0.0`
- Title: `Project Apollo v1.0.0 — Mobile Command Environment Baseline`
- Release summary: initial governance, security, device-mode, NetWatch, recovery, visual-identity, and portfolio-safe documentation release.

## Local publication sequence

From the directory containing this repository:

```text
git init
git add .
git status
git commit
git branch -M main
git remote add origin <REPOSITORY_URL>
git push -u origin main
```

Enter the recommended subject and description in the commit editor. Inspect `git status` and the staged diff before committing. Do not paste credentials into the remote URL.

