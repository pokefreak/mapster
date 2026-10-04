# 🗺️ Mapster: Advanced World Map Enhancement

Mapster is a lightweight, high-performance world map overhaul designed for the **PrimordialWoW Network** client. It replaces the restrictive, bulky native Blizzard map framework with a highly customizable, fluid interface that enhances navigation, group coordination, and world exploration without causing interface lag.

---

## 🌟 Core Feature Presentation

### 👁️ Adjustable Alpha Transparency & Motion Controls
* **On-The-Move Visibility:** Seamlessly fades the map window to a custom transparency level the moment your character begins moving.
* **Fluid Interactivity:** Allows players to run, react to world combat encounters, and navigate zones simultaneously without opening and closing the map interface constantly.

### 📍 Precision Coordinate Grid Overlay
* **Dual-Axis Tracking:** Embeds real-time X/Y numeric cursor grid markers and player position variables directly onto the map frame.
* **Group Synergy:** Plots exact coordinates for party and raid members, optimizing rally points, world boss positioning, and rare-spawn calls.

### ☁️ Fog-of-War De-shrouding
* **Zone Discovery Preview:** Cleanly de-shrouds unexplored map sectors and sub-zones with high-contrast outlines.
* **Visual Continuity:** Preserves local server quest boundaries while showing flight paths and point-of-interest structures ahead of time.

### 📐 Modular Window Scaling & Layouts
* **True Windowed Mode:** Strips away the forced full-screen lock of the default 3.3.5a client map.
* **On-the-Fly Scaling:** Shrinks or expands map dimensions dynamically, freeing up real estate on your monitor screen.

---

## ⚙️ Technical Blueprint & Engine Performance

Unlike legacy map modifications that continuously flood the UI thread with coordinate redraw updates, Mapster is optimized to preserve high framerates during intensive gameplay:

* **Zero-Spam Hooks:** Uses lean script loops that only fire coordinate changes when your cursor or character moves.
* **Memory Conservation:** Runs on an extremely light data footprint, keeping UI memory allocation low.
* **Total Module Toggle:** Built-in modular options allow users to toggle coordinate lines, sub-zone text overlays, and scaling frames individually from the in-game AddOn menu.
