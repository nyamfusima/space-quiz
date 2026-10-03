# Copilot instructions

## Project overview

- This is a small, standalone space exploration quiz implemented in `index.html`.
- The page must work when opened directly from disk with `file://`; do not add a server, build step, package manager, or external dependency.
- Keep the quiz responsive and preserve its mission-control design, light and dark themes, and reduced-motion support.

## Implementation

- Prefer small, focused changes in the existing HTML, CSS, and vanilla JavaScript.
- Keep the quiz usable with a keyboard and assistive technology: use semantic controls, visible focus indicators, logical focus movement, accessible feedback, and a labeled progress indicator.
- Respect `prefers-reduced-motion` for all decorative and interaction animations.
- Preserve the ten-question flow, answer feedback, score tracking, and results/restart behavior when changing quiz interactions.
- Keep decorative icons and visual flourishes from adding redundant screen-reader output.

## Verification

- For behavior or interaction changes, open `index.html` in the integrated browser and verify the affected flow.
- Check both correct and incorrect answers, score/progress updates, and results/restart when relevant.
- Exercise keyboard navigation without a mouse when changing focus or controls.
- For markup or style-only changes, verify the relevant responsive, theme, accessibility, or reduced-motion behavior.
