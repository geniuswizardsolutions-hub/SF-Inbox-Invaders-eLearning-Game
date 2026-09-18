# SF-Inbox-Invaders-eLearning-Game
# Inbox Invaders — Shield Grid Defense (Salesforce version)

Client-facing build of the security awareness training PoC — a retro arcade-styled scenario game covering targeted impersonation attacks on executive assistants.

**This repo is private and client-specific.** Company name, tools, and workflows referenced in the game (Coupa, Amex, LinkedIn, Google Drive, ClickFix) are tailored to the client's actual environment and should not be reused in the public portfolio version of this project.

## Sectors

- **Sector 1 — The Wire Request**: financial impersonation & payment redirection (3 rounds)
- **Sector 2 — The Access Grant**: privilege creep & unauthorized system access (2 rounds)

Each sector mixes one legitimate, properly-scoped request in with risky ones, so the lesson is discernment rather than blanket suspicion. Each sector ends with a Security Team reporting checkpoint.

A third sector ("The Credential Request" — MFA/vishing, phishing links, remote access) is written and held in reserve; see the scenario script doc for full content.

## Tech

Single self-contained `index.html` — no build step, no dependencies, no backend. Pure HTML/CSS/JS with a canvas-based animation engine. Runs in any modern browser.

## Status

In review with client. Scenario script (Word doc) is the source of truth for content — update it first, then mirror changes into `index.html`.
