# Desktop Widgets

A SolidJS + Effect-TS terminal UI project that taught me more than it shipped.

---

## 🪦 Memorial Plaque

> _Here lies the Desktop Widgets Project (2024)_
>
> - Spawned 3 working binaries
> - Consumed 570MB RAM
> - Taught Effect-TS to one developer
> - Never achieved cava wallpaper integration
> - Rest in peace

---

## What It Actually Does

- **`bar`** - A status bar (clock + stats) running in a kitty panel (288MB RAM)
- **`launcher`** - An app launcher with fuzzy search (283MB RAM)
- **`dashboard`** - A daemon manager that can... start the status bar

## What It Was Supposed To Do

- [ ] DBus bindings for system integration
- [ ] Full-screen dashboard with widgets
- [ ] OSD notifications via kitty kittens
- [ ] Wallpaper manager with wbg integration
- [ ] Music visualizer using cava + kitten
- [ ] Dynamic wallpaper changes based on music

## The Stack

```
Your "Bar" Architecture:
┌─────────────────────────────────────┐
│  SolidJS UI (React-like framework)  │
├─────────────────────────────────────┤
│  @opentui/solid (terminal UI lib)   │
├─────────────────────────────────────┤
│  Effect-TS (functional programming) │
├─────────────────────────────────────┤
│  Bun runtime (JavaScript engine)    │
├─────────────────────────────────────┤
│  Kitty terminal (GPU-accelerated)   │
├─────────────────────────────────────┤
│  kitty +kitten panel (window mgr)   │
└─────────────────────────────────────┘
```

## Why Keep It?

This project got me into **Effect-TS**. Every time I write `Effect.gen`, `Atom.make`, or design a service layer, I'm building on what I learned here.

The RAM usage? That's the cost of education.

## Usage

```bash
# Build
bun run build

# Run the bar (in a kitty panel)
bun run start:bar

# Run the launcher
bun run start:launcher

# Run the dashboard
bun run start:dashboard
```

## Dependencies

- [SolidJS](https://www.solidjs.com/) - Reactive UI framework
- [Effect-TS](https://effect.website/) - Functional programming toolkit
- [@opentui/solid](https://github.com/erickisos/opentui) - Terminal UI components
- [Bun](https://bun.sh/) - JavaScript runtime
- [Kitty](https://sw.kovidgoyal.net/kitty/) - GPU-accelerated terminal

## The Real Achievement

> "I once built a status bar that used more memory than Chrome."

That's a flex. 💪

---

_Love it for what it was, learn from it, and let it rest in the graveyard of "ambitious projects that taught me stuff."_

---

**Note:** This README was written by an AI assistant (Kimi K2.5) after roasting the project for its overengineering and then feeling guilty about it.
