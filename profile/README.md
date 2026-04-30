# Modbit Studios

> Mobile games. Fast. Profitable. Fun to build.

We're a mobile game studio built around one idea: **reusable microsystems that snap together like Lego.**  
New trend hits? We ship a game in days, not months.

---

## How we build

Most studios build games from scratch every time. We don't.

Every game we ship adds to a growing library of battle-tested modules — physics rigs, scoring systems, ad hooks, UI kits, progression loops, input handlers, juice effects. When the next viral moment drops, we pull what we need, wire it together, and launch.

```
trend drops → pick modules → build the delta → ship → monetize → repeat
```

The more we ship, the faster we get. The faster we get, the more we earn.

---

## Repo structure

| Prefix | What lives there |
|---|---|
| `core-*` | Foundational systems every game can use (ads, analytics, save state, IAP) |
| `module-*` | Standalone gameplay microsystems (physics, grid, drag, timer, swipe) |
| `ui-*` | Reusable UI components (menus, HUD, popups, onboarding flows) |
| `game-*` | Shipped game projects — assembled from modules above |
| `tools-*` | Internal tooling, build scripts, CI pipelines |

---

## Module philosophy

A good module does **one thing** and does it well.

- Self-contained — no hidden dependencies on other modules
- Config-driven — behavior controlled by a single settings file
- Drop-in ready — documented, tested, example scene included
- Monetization-aware — ad slots and IAP hooks are first-class, not bolted on after

If a module can't be dropped into a new project in under 30 minutes, it needs to be refactored.

---

## What we're building toward

- A library deep enough that most new games are just **config + art**
- Fast enough iteration to chase trends **before they peak**
- A back catalog of live games generating **passive ad and IAP revenue**
- A small, high-trust team that ships and has fun doing it

---

## Contributing

All work happens in feature branches. PRs require:

1. The module works as a standalone drop-in
2. A README in the repo root explaining what it does and how to configure it
3. At least one example scene
4. No hard-coded references to a specific game project

We move fast but we don't leave messes. A module that's a pain to reuse isn't a module — it's just code.

---

## The goal

Make great mobile games. Make money. Have fun doing it.

In that order, roughly.

---

*Modbit Studios — build once, launch forever.*
