<div align="center">

<h1 id="header" align="center">
    <pre>Hi! I'm Sami :)</pre>
  </h1>

I build agent tooling, a Wayland compositor, and reproducible Nix systems — including [my NixOS configuration](https://github.com/y0usaf/nixos).

<img src="assets/cookunity.png" width="16" height="16" alt="CookUnity"/> I'm currently an AI-Native Software Engineer at [CookUnity](https://cookunity.com/)! <img src="assets/cookunity.png" width="16" height="16" alt="CookUnity"/>

</div>

---

<img src="assets/cookunity.png" width="16" height="16" alt="CookUnity"/> [CookUnity](https://cookunity.com/) · <img src="assets/rootly.png" width="16" height="16" alt="Rootly"/> [Rootly](https://rootly.com/) · <img src="assets/cohere.png" width="16" height="16" alt="Cohere"/> [Cohere](https://cohere.com/)

## Flagship projects

**[tomoe](https://github.com/y0usaf/tomoe)** — A Wayland compositor on Smithay: its Rust core owns mechanism (windows, outputs, input, and an infinite-canvas camera), while all policy (tiling, workspaces, and focus) lives in hot-reloaded Lua.

`Rust · Smithay · Lua`

**[ekko](https://github.com/y0usaf/ekko)** — An extension-first terminal multiplexer whose daemon owns PTYs and vt100 state, clients attach over a versioned Unix socket, and every stock feature is built against the public `ekko-ext` API.

`Rust · PTY · Unix sockets · Lua`

**[pi-flake](https://github.com/y0usaf/pi-flake)** — A Nix flake that builds the pi coding agent from source and packages roughly 15 extensions with builder functions for downstream flakes.

`Nix · TypeScript · JavaScript`

**[balatroAI](https://github.com/y0usaf/balatroai)** — Bots play Balatro through one JSON-RPC surface, using the live Steam game for narrated demos or an in-process simulator running roughly 1,500 games/sec: train on the sim, demo on the real game.

`Python · JSON-RPC · reinforcement learning`

**[codex-desktop-flake](https://github.com/y0usaf/codex-desktop-flake)** — Repackages OpenAI’s macOS-only Codex Desktop into a working Linux/NixOS app by extracting its asar, rebuilding native modules, and repacking Electron.

`Nix · JavaScript · Electron`

`manzil` — Tiny home management for NixOS, nix-darwin, and finix: a small module, Rust manifest linker, and JSON manifests.

## Merged upstream contributions

- **finix:** made dinit work as PID 1 and added a VM boot test in [finix#3](https://github.com/willowispll/finix/pull/3).
- **hyprpaper:** added opt-in recursive wallpaper directory scanning in [hyprpaper#349](https://github.com/hyprwm/hyprpaper/pull/349).
- **Handy:** switched Nix packaging from the AppImage to building from source in [Handy#778](https://github.com/cjpais/Handy/pull/778).
- **Handy:** added a Nix flake for NixOS support in [Handy#561](https://github.com/cjpais/Handy/pull/561).
- **tweakcc:** fixed bunx cache version handling when patching Claude Code in [tweakcc#282](https://github.com/Piebald-AI/tweakcc/pull/282).
