# Prompt Log

## 2026-11-18

- **Asked:** Set up the top-level project files and numbered folders for a single-file GitHub Pages web app.
- **Changed:** Created `index.html`, `spec.md`, `prompts.md`, four numbered folders with short README files, and project layout rules in `AGENTS.md`.
- **Result:** Worked; no application code or other project functionality was added.

## 2026-11-18

- **Asked:** Read `spec.md`, summarize the app, and assess overall completeness and section order without adding implementation details.
- **Changed:** No files; reviewed the specification only.
- **Result:** Identified that the app is a beam analysis tool and noted missing requirements and section-order issues for a follow-up discussion.

## 2026-11-18

- **Asked:** Work only on the Inputs section of `spec.md`, identify missing inputs, and verify units, ranges, defaults, and controls.
- **Changed:** Expanded `spec.md` with detailed controls and defaults/ranges for support type, span, point and uniform loads, member selection, grades, section properties, and allowable bending stress.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Build Stage 1 of the app as a single-file HTML/CSS/JavaScript mockup with realistic placeholder values and no calculations.
- **Changed:** Replaced `index.html` with the desktop/mobile mockup, complete input controls, beam sketch, shear/moment/deflection plot placeholders, summaries, pass/fail cards, theme switching, and basic point-load/member/mobile interactions.
- **Result:** Worked; no structural calculations were implemented.

- **Asked:** Work only on the Calculations section, check equations and units, define variables, and identify missing output calculations.
- **Changed:** Expanded `spec.md` with equilibrium, shear/moment, deflection, bending stress, deflection limit, sign conventions, unit conversions, and governing-value definitions.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Finalize the Calculations and Outputs sections in `spec.md` without building the app.
- **Changed:** Kept the detailed calculation requirements and expanded Outputs with beam/load sketch behavior, three diagrams, deflection views, result summaries, precision, and invalid-input behavior.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Work on the Look and feel section of `spec.md` only.
- **Changed:** Added visual style, light/dark themes, status colors, desktop/mobile layouts, typography, initial state, and automatic-update behavior.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Work on the Validation section of `spec.md` only.
- **Changed:** Added primary, no-load, cantilever, combined-load, upward-load, bending-failure, deflection-failure, tolerance, and repeatability requirements.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Work on the Out of scope section of `spec.md` only.
- **Changed:** Expanded exclusions to unsupported beam systems, structural checks, loading types, 3D modeling, optimization, drawings, code certification, and initial export.
- **Result:** Worked; no code or application functionality was added.

## 2026-11-23

- **Asked:** Build Stage 2 of the app: complete inputs, presets, validation, and Load Example behavior without structural calculations.
- **Changed:** Updated `index.html` to start blank, add member presets, dynamic point-load location limits, field-level validation, valid-input status, and clearly named empty calculation-function boundaries for later stages.
- **Result:** Worked; no structural calculations or drawing code changes were implemented.

## 2026-11-23

- **Asked:** Build Stage 3 only: reactions, shear, moment, and beam/load sketch.
- **Changed:** Added separate reaction and shear/moment calculation functions plus separate SVG drawing helpers for the beam sketch, shear diagram, and moment diagram. Valid inputs now update reaction cards and governing shear/moment values.
- **Result:** Worked; deflection and design-check calculations remain deferred to later stages.

## 2026-11-23

- **Asked:** Build Stage 4 only: deflection, bending stress, utilization, and pass/fail checks.
- **Changed:** Added unit-converted deflection calculation, bending stress and utilization calculations, live true-scale and magnified deflection plots, governing-value updates, and pass/fail card rendering.
- **Result:** Worked; responsive and full validation work remain for the final stage.

## 2026-11-23

- **Asked:** Build Stage 5: finish responsive behavior, invalid-state handling, and validation coverage.
- **Changed:** Added compact-height and keyboard-focus polish, live/invalid results labels, cleared result values for invalid inputs, and a repeatable validation table in `02_validation/validation-cases.md`.
- **Result:** Worked; the app is complete for the specified five-stage scope.

## 2026-11-23

- **Asked:** Add an option to run the beam calculation after the user enters data.
- **Changed:** Added a disabled-until-valid “Run Calculation” button, changed validation to stop automatic recalculation, cleared stale results after input changes, and preserved the existing calculation functions.
- **Result:** Worked; calculations now run only after the button is pressed.

## 2026-11-23

- **Asked:** Add the approved side-by-side comparison and printable calculation sheet requirements to `spec.md` without building the app.
- **Changed:** Added detailed specification sections for unlimited local saved configurations, dedicated A/B comparison mode, result-only difference highlighting, print-sheet content, and US Letter landscape print layout.
- **Result:** Worked; no application files or code were changed.

## 2026-11-23

- **Asked:** Build the side-by-side comparison and printable calculation sheet features.
- **Changed:** Added dedicated comparison mode, unlimited `localStorage` configurations, Add/Duplicate/Rename/Delete controls, separate A/B inputs and Run actions, result-difference highlighting, and a three-column print layout with compact diagrams and sheet metadata.
- **Result:** Worked; the updated single-file app served successfully for a local HTTP smoke check.
