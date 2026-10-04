# Contributing to Life Signs

Use this repository for the wider Life Signs concept, shared direction and implementation links. Put X4-specific code, architecture, setup and testing documentation in [X4LifeSigns](https://github.com/yeahmyusernameis32characterslong/X4LifeSigns).

Before working on the X4 implementation, read its [AGENTS.md](https://github.com/yeahmyusernameis32characterslong/X4LifeSigns/blob/main/AGENTS.md) and relevant project documents.

Keep changes small, focused and easy to review. Use a task branch and open a pull request against the repository's default branch. Do not push directly to main or bypass its protections.

Describe what changed and how it was checked. Distinguish proposed behaviour, implemented behaviour and behaviour verified inside the game. Do not present design choices or simulated tests as proof of a working X4 integration.

Keep credentials, tokens and other secrets out of contributions.

## Local setup privacy

Keep actual machine paths and private setup notes in `SETUP.local.md` at the repository root. Create this file locally if needed; Git ignores it, along with `.env` and `.env.*` files such as `.env.local`. This is a local notes convention, not an implemented configuration loader.

Use `%USERPROFILE%`, `<X4 profile id>` or `<X4 user data folder>` in shared examples instead of personal usernames, OneDrive account paths or profile IDs. `%USERPROFILE%` is Command Prompt syntax; PowerShell uses `$env:USERPROFILE`. Replace angle-bracket placeholders locally before using a path. Generic installation paths may remain useful public examples.

Keep X4-specific setup guidance in X4LifeSigns. Sanitise any paths in commits, issues, pull request descriptions, screenshots and diagnostic extracts before publishing.

Before committing, run `git check-ignore SETUP.local.md .env.local`, then review `git status --short` and `git diff --cached`. Ignore rules do not protect files already tracked by Git; do not force-add private local files.
