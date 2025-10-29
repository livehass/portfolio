---
title: "Travel backpack using LocalStorage"
date: 2025-10-28
description: "A travel backpack checklist crafted with JavaScript, CSS, and HTML, using localStorage and JSON parsing to persist user data locally in the browser."
image: "/images/projects/1.png"
link: "https://travel-backpack-with-local-storage.vercel.app/"
repo: "https://github.com/livehass/Travel-backpack-with-localStorage"
tech:
  - "JavaScript"
  - "HTML"
  - "CSS"
---

A compact and practical travel checklist designed to help travelers plan and store their packing lists locally. The app demonstrates a small, maintainable architecture: a clear separation between UI rendering, data persistence (via `localStorage`), and JSON-driven list management.

## Key Features

- Persistent checklist using `localStorage` so lists survive page reloads.
- JSON-based data model for easy import/export and programmatic manipulation.
- Responsive UI built with semantic HTML and CSS for quick customization.

## Notes for maintainers

Keep UI logic small and modular. The data layer uses a simple JSON schema (array of items with id, label, checked) — tests and migrations should operate on that shape.
