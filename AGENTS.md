# Project guidance

## Overview

This project is a standalone space-exploration quiz. The complete application lives in `index.html`; it runs directly in a browser without a server, build step, or external dependencies.

## Working in this project

- Keep the app self-contained in `index.html`. Do not add frameworks, packages, network-loaded assets, or server requirements.
- Preserve the quiz's 10-question flow, progress and score indicators, answer feedback, and results/restart experience.
- Keep the layout responsive and centered in a narrow column. Preserve light/dark system themes, accessible keyboard interaction, and reduced-motion support.
- Use semantic HTML, visible focus states, and sufficient theme-aware contrast. Keep decorative effects non-interactive and hidden from assistive technology when appropriate.
- Prefer small, focused edits and follow the existing naming and formatting conventions.

## Validation

- Open `index.html` directly in a browser and verify the affected interaction or appearance.
- For quiz behavior changes, check keyboard navigation, score and feedback states, progression through all questions, and the final results/restart flow.
- There is no package manager, build, or automated test setup; do not introduce one for routine changes.
