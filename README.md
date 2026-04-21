# Lab 3 - Adding CSS to Meeting Minutes

CSE 110 - Spring 2026

## GitHub Pages URL

Live at: https://salwazir.github.io/sp26-cse110-lab3/

Status: built and served over HTTPS from `main` branch (root).

## Overview

This lab takes the HTML meeting-minutes page from Lab 2 and adds a CSS layer
on top of it. The styling demonstrates the full Lab 3 CSS checklist
(selectors, combinators, colors, units, box model, layout with flexbox and
grid, responsiveness, and new-in-2023 selectors such as `:has()` and
nested selectors).

## File Layout

- `index.html` - structured meeting minutes (linked to external styles, an
  internal `<style>` block, and one inline style)
- `styles.css` - external stylesheet (the bulk of the CSS)
- `standup.md` - Agile standup notes template
- `.github/ISSUE_TEMPLATE/` - issue templates used when filing new issues
- `screenshots/` - includes the CSS validator screenshot
- `assets/` - images, audio, and video used on the page

## Agile Workflow (Part 1)

Issues, labels, and pull requests for this lab are tracked in this
repository's Issues and Pull Requests tabs. Each issue represents a
discrete task; PRs are merged one-per-issue through a feature branch.

## On `:has()` and nested selectors

Both selectors were widely adopted in 2023. Older browsers (and users who
have not updated in a long time) may not support them - see
[caniuse.com](https://caniuse.com/). When these features are essential
for layout, provide a plain-CSS fallback so the page still renders
correctly for users on older browsers.
