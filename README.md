<div align="center">

# 🌙 Moon Animator 2 — API Documentation

[![GitHub Pages](https://img.shields.io/badge/docs-live-c87dff?style=for-the-badge)](https://troublegy.github.io/Moon-Animator-2-API/)
[![Moon Animator](https://img.shields.io/badge/version-34000-8b44cc?style=for-the-badge)](https://www.roblox.com/library/4725618216/Moon-Animator-2)
[![Lua](https://img.shields.io/badge/lua-luau-569cd6?style=for-the-badge)](https://luau-lang.org/)

**Unofficial API reference for Moon Animator 2 Roblox plugin**

Access internal functions, windows, easings, classes and learn plugin modding via `_G.MoonGlobal`

[📖 **View Documentation**](https://troublegy.github.io/Moon-Animator-2-API/)

</div>

---

## 📚 What's Inside

- **Easing Functions** — 44+ interpolation functions (Sine, Quad, Cubic, Elastic, Bounce...)
- **Windows** — 28 UI windows with properties and size constraints
- **Menus** — Context menus and menu bar item access
- **Constants** — Frame limits, FPS, handle settings
- **Classes** — 50+ ModuleScript references (Tracks, UI Components, Core)
- **Themer** — Theme system and color management
- **Plugin Modding** — Complete examples for extending Moon Animator

---

## 🚀 Quick Start

```lua
local _g = _G.MoonGlobal

-- Wait for Moon Animator to load
repeat
    _g = _G.MoonGlobal
    task.wait(0.5)
until _g and _g.ready

-- Use easing functions
local eased = _g.EasingFunctions.QuadOut(0.5) -- 0.75

-- Access windows
print(_g.Windows.MoonAnimator.Visible)

-- Require classes
local Ease = require(_g.class.Ease)
```
---

## 🔗 Links

- 📖 [**Live Documentation**](https://troublegy.github.io/Moon-Animator-2-API/) — Full API reference
- 🌙 [**Moon Animator 2**](https://www.roblox.com/library/4725618216/Moon-Animator-2) — Roblox plugin page
- 👤 [**xsixx**](https://www.roblox.com/users/9543399/profile) — Plugin developer

---

## ⚠️ Disclaimer

This is **unofficial documentation** created for plugin developers.

- Not affiliated with Moon Animator developers
- API structure may change between versions
- Based on version **34000**

---

<div align="center">

Made with 💜 for the Roblox animation community

</div>
