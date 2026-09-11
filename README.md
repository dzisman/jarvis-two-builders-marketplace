# Jarvis · One Platform, Two Builders

This is the small, shared Codex marketplace for Danyel and Femke. It installs the Jarvis connector without downloading or opening a Mac command script.

Jarvis uses each person's own ChatGPT sign-in. Personal tasks, research, memory, credentials and chat history stay with that signed-in account. Approved module changes, functions, prompts, tests, corrections and release notes are shared between both builders.

## Install

1. Install and open the Codex desktop app, then sign in with your own ChatGPT account.
2. Add this marketplace: `codex plugin marketplace add dzisman/jarvis-two-builders-marketplace`
3. Install Jarvis: `codex plugin add jarvis-two-builders@jarvis-builders`
4. Start a new Codex task, select Jarvis, and approve the personal Jarvis connection when prompted.

The Jarvis tools run from the hosted platform. Normal tool and module updates therefore arrive for both builders through the same live service without another installer download.

## Update the small connector package

If the dashboard says the connector package itself is out of date, refresh it with:

`codex plugin marketplace upgrade jarvis-builders && codex plugin add jarvis-two-builders@jarvis-builders`
