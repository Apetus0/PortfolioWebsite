# Realmwalker Portfolio Website

A multi-page, responsive portfolio concept engineered with semantic HTML5, custom CSS layout models, and native JavaScript state tracking. Built around an immersive high-fantasy concept, the project serves as a showcase for core frontend engineering competencies, complex form management, media integration, and container layout dynamics.

---

## Architectural Highlights

* **Cross-Linked Multi-Page Core:** Features an interconnected structure linking standard pages (`resume.html`, `cover-letter.html`, `career-goals.html`) to establish smooth sub-domain navigation.
* **Bi-Directional Structural Flow:** Employs precise side-by-side positioning leveraging `float` structures paired with `box-sizing: border-box` resets to ensure structural calculations scale reliably.
* **Native Runtime Clock Execution:** Integrates an asynchronous polling routine via native JavaScript `setInterval` to parse, update, and display formatted time matrices inside DOM containers in real-time.
* **Component-Level Fluid Adjustments:** Implements explicit `@media` boundary rule sets targeting distinct viewport limits to gracefully rearrange structural columns into single vertical flows for flawless mobile execution.

---

## Project Structure & File Map

* `career-goals.html` / `cover-letter.html` / `resume.html`: Core markup pages utilizing modern HTML5 semantic structural layout blocks (`<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`).
* `style.css`: A comprehensive style architecture utilizing specific element hooks, pseudo-selectors (`:hover`), image-positioning rules, data-table borders, and custom theme layouts.

---

## Technical Implementations

### Complex Form Architecture
Implements a multi-input data collection asset designed to pass payload values securely using standardized `POST` methods:
* Custom structured layouts mapping textual user fields (`<input type="text">`, `<textarea>`).
* Dynamic validation filters managing communications configurations (`<input type="email">`, `<input type="tel">`).
* Grouped contextual selection widgets using radio items matched directly to explicit labels via matching `for` identifiers.

### Rich Media Containers
* **Embedded Video Buffering:** Integrates custom `<video>` tags utilizing native player controls and strict `max-width` responsive sizing parameters.
* **Asynchronous Audio Rendering:** Features native HTML5 `<audio>` container injection to support multi-format audio streams without third-party extension overhead.

---
