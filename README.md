# Shadow Tool ☀

A small bench lab for CSS shadows. Design layered `box-shadow`, `filter: drop-shadow()` and `text-shadow` by dragging a sun around the stage, then steal the CSS.

**[→ Open Shadow Tool](https://tcboni.github.io/shadow-tool/)**

## Features

- **Draggable light source** — click or drag anywhere on the stage. Angle sets the shadow direction; elevation sets the "throw" (low sun → long shadows, 100% is high noon). Linked layers (☀) follow the light together; unlink any layer for manual x/y control.
- **Three targets** — box (`box-shadow`), shape (`filter: drop-shadow()`, which hugs transparency and holes), and text (`text-shadow`).
- **Layer stack** — add, duplicate, reorder, hide and delete layers inline; per-layer distance/offset, blur, spread, opacity, color and inset.
- **11 presets** — including _Near / Mid / Far_, three graduated elevations in the style of Josh Comeau's shadow palettes, plus hard-edged _Pop_ and _Cel_, 16-step _Long_, _Neon_/_Aura_/_Ring_ glows on dark stages, neumorphic _Puff_, and inset _Well_. Every preset dresses the whole stage — background, fill, radius, and light position.
- **Random** (button or press `R`) — rolls a complete, tasteful shadow: light position, stage colors and a curated style family (soft cascade, pop, long, cel, glow, aura, neumorph…).
- **Undo / redo** — header arrows or `⌘Z` / `⇧⌘Z`.
- **Output formats** — plain CSS, a CSS custom property block, or a Tailwind arbitrary-value class. Syntax-tinted, one-click copy.
- CSS-only tooltips built on CSS anchor positioning, keyboard-accessible light source, responsive two-column layout, state persisted to `localStorage`.
