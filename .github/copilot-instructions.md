# Copilot instructions

## Project structure

- The app is a standalone browser quiz. Its markup, styles, quiz data, and JavaScript live in the root `index.html`.
- Keep the app runnable by opening `index.html` directly. Do not add a server, build step, package manager, framework, or external dependency.

## Implementation conventions

- Make focused changes in `index.html` and preserve the existing 10-question quiz flow, score and progress indicators, answer feedback, results, and restart behavior.
- Keep the layout responsive and centered in a narrow column. Use the existing CSS custom properties for colors and preserve `prefers-color-scheme: light dark` support.
- Keep interactive controls semantic and keyboard accessible. Preserve visible focus indicators, meaningful accessible names and progress information, and live feedback announcements.
- Respect `prefers-reduced-motion` for animated effects. Keep decorative elements non-interactive and hidden from assistive technology.
- Follow the existing vanilla HTML, CSS, and JavaScript style. Do not introduce unrelated features or abstractions.

## Validation

- Preview `index.html` directly in the integrated browser after UI changes.
- For quiz interaction changes, check keyboard navigation, correct and incorrect answers, score updates, progress through all 10 questions, results, and restart.
- There is no automated test runner or build configuration. Use the browser for validation rather than introducing tooling for routine edits.
