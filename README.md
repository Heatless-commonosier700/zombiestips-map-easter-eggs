# ZombiesTips v2026 - Call of Duty Zombies Easter Egg Guide

> A community-built collection of Easter egg walkthroughs for Call of Duty Zombies maps. Accessible by design and ready for GitHub Pages.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-GitHub%20Pages-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevinio38/zombiestips-map-easter-eggs?style=flat-square)](https://github.com/kevinio38/zombiestips-map-easter-eggs)

---

<p align="center">
  <a href="https://kevinio38.github.io/zombiestips-map-easter-eggs/">
    <img src="https://img.shields.io/badge/Download-ZombiesTips%20Guide-brightgreen?style=for-the-badge" alt="Download ZombiesTips Guide">
  </a>
</p>

> **[Direct Download - ZombiesTips](https://kevinio38.github.io/zombiestips-map-easter-eggs/)**

---

[Download Latest Build](https://kevinio38.github.io/zombiestips-map-easter-eggs/)

---

## What it is

ZombiesTips provides clear, phase-by-phase Easter egg instructions for Call of Duty Zombies maps, with accessibility treated as a first-class requirement. The walkthroughs split difficult quests into practical chunks, and each one includes recommended loadouts, boss encounter phase notes, and a progress tracker. The aim is to make demanding Easter eggs easier to tackle for both new players and long-time fans.

The project is built for deployment on GitHub Pages, with collapsible content blocks and sticky navigation that help keep guides usable during live play. Recent work centers on WCAG 2.1 AA compliance so the pages remain dependable with screen readers and keyboard-only use. Motion is also adjusted to respect the `prefers-reduced-motion` setting for a more comfortable experience.

---

## Script Features

- Collapsible step-by-step sections for each Easter egg phase
- Progress tracker with step counter to monitor completion
- Sticky navigation with jump links for quick section access
- Mark Complete checklist to track finished steps
- Loadout and gobble gum recommendations for each map
- Boss fight phase breakdowns with strategies
- WCAG 2.1 AA compliant design
- Keyboard navigation and screen reader compatible
- `prefers-reduced-motion` support for accessibility

---

## Getting Started

Clone the repository and serve the files from any static host or GitHub Pages. There is no build pipeline to install - open `index.html` in a browser locally, or publish the folder as-is.

```
git clone https://github.com/kevinio38/zombiestips-map-easter-eggs.git
cd zombiestips-guides
```

Open `index.html` locally or push to GitHub Pages for live hosting.

---

## Options

| Setting | Description |
|---------|-------------|
| `data-collapsible` | Enables expand/collapse for guide sections |
| `data-progress` | Toggles step counter display |
| `data-checklist` | Activates Mark Complete checkboxes |
| `data-reduced-motion` | Disables animations for accessibility |

Add these attributes to the guide container element to customize behavior.

---

## Compatibility

- Works with all major browsers (Chrome, Firefox, Safari, Edge)
- Fully functional on mobile devices with touch navigation
- Supports Call of Duty Zombies maps across Black Ops series and Modern Warfare
- Known limitation: Some older browser versions may not support CSS `:has()` selector used for collapsible sections

---

## FAQ

**How do I add a new map guide?**  
Copy the current HTML template, create a new guide page from it, and add the new entry to the main navigation.

**Will updates break my existing guides?**  
The project follows semantic versioning, and any breaking changes will be called out in the release notes.

**Can I customize the styling?**  
Yes. Update the CSS variables in `style.css` to fit the look you want.

**Does this work offline?**  
Yes. Everything needed is bundled locally, so no external dependencies are required.

**How do I report an accessibility issue?**  
Open an issue in the repository and include the problem details plus the assistive technology you used.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
