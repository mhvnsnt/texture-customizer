# HANDOFF — texture-customizer

**Last updated: 2026-11-22 (America/New_York).**
**Repo:** `mhvnsnt/texture-customizer` (PUBLIC), default branch `master` (NOT `main`).
**Purpose of this file:** any agent that picks up work here reads this FIRST, then the linked docs. It states what we've done, where we're at, and what we're working toward — so the owner can say "go to this repo, pick up the work" and you just know. Update this file in the same PR whenever the state changes (add, don't delete).

## 1. What this repo is

The texture customizer — a browser PWA for customizing textures. The repo carries no description, so what follows is only what the tree shows: `index.html` + `app.js` + `styles.css` (the app), `manifest.json` + `sw.js` + `icon-192.png` + `icon-512.png` (the PWA shell — installable, works offline), `docs/`, `AGENTS.md`, `WORKING-METHOD.md`. Created 2026-10-05. Public. Default branch is `master`, not `main`.

**Plainly:** the repo does not say in its own words what it customizes textures for (which game, which models). Whoever picks this up should read `docs/` and `app.js` first and write the purpose down here before building more.

## 2. Where we're at

### DONE
- **Anti-clobber laws (2026-10-17, PR #3 merged):** the owner's anti-clobber laws landed after the DXMMII 54k-file wipe.
- **Working method statement (2026-10-27):** `WORKING-METHOD.md` landed.

### IN PROGRESS
- Nothing is actively in progress in this repo that the repo itself records. Last push was the 2026-10-27 sweep commit. No open PRs, no releases.

### BLOCKED
- Nothing recorded as blocked. The gap is a documentation gap, not a code block: the purpose is unstated (see §1).

## 3. What we're working toward

First: establish what it customizes textures for, from `docs/` and `app.js`, and write it into this file and the README. Then: the customizer works as a PWA — open it, customize a texture, and the result is usable in the game or model it is for. The bar: the purpose is written down in the repo's own words before more features land, and textures ship baked in, judged against the original model.

## 4. Standing rules that apply here

- **Branch → PR → merge, always — base is `master`.** Never push to master directly. Add-only, zero-conflict PRs, no force pushes.
- **Checkpoint-and-save law:** CHECKPOINT.md first, update after every step; the repo is the save; resume, never restart.
- **No-temp-storage law:** nothing in /tmp or any wipeable location, ever.
- **Real-source-only:** build from the real sources, wired up fully — no hand-tooled lookalikes.
- **Never kill in-progress work.**

## 5. Key files and paths

| What | Where |
|---|---|
| App | `index.html`, `app.js`, `styles.css` |
| PWA shell | `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png` |
| Docs | `docs/` |
| Agent rules | `AGENTS.md` |
| Method doc | `WORKING-METHOD.md` |

## 6. Open decisions needing the owner

- **What it customizes textures for:** the repo does not state it. Once a pickup lane reads the docs and the app, the purpose still needs his confirmation before it is written in as fact.
- No other decisions are recorded in this repo.

## 7. How to pick up

1. Read this HANDOFF.md first, then `docs/`, `app.js`, and `README.md`.
2. Write down what it customizes textures for (from those sources, not from guessing) and get the owner's confirmation before treating it as fact.
3. Check what other agents are already doing before starting anything.
4. Resume from the stated next step — never restart, never re-derive finished work.
5. Land work branch → PR → merge (base `master`), add-only. Stage finished work to the repo as it lands.
6. Update this HANDOFF.md in the same PR when the state changes. Verify with your own eyes before claiming anything done.
