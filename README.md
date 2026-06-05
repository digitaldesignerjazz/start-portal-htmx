# Start Portal + HTMX

**Dynamic, hypermedia-driven version of the NexusSpace control center**

This repository is the experimental ground for making **Start Portal** dynamic using **HTMX** + Tailwind CSS.

Instead of heavy JavaScript frameworks, we extend HTML with attributes to add AJAX-like behavior, real-time updates, loading states, and interactive actions — while keeping everything extremely lightweight and simple.

## Why HTMX?

- Only ~14KB
- No build step required
- Works beautifully with Tailwind
- Perfect for dashboards and control interfaces
- Excellent productivity and simplicity
- Easy to evolve into a proper backend later (FastAPI is the most popular pairing)

## Current Features (HTMX-powered)

- Auto-refreshing Recent Activity feed
- Start buttons with loading states and feedback
- Status indicators that can be updated dynamically
- Theme switcher (persisted)
- Beautiful, responsive Tailwind UI

## Tech Stack (Current)

- **Frontend**: Single-file HTML + Tailwind (CDN) + HTMX (CDN)
- **Future**: Lightweight backend (FastAPI recommended) for real data and actions

## Getting Started

```bash
git clone https://github.com/digitaldesignerjazz/start-portal-htmx.git
cd start-portal-htmx
# Open index.html in your browser
```

The dashboard works immediately. HTMX features will become more powerful once a backend is added.

## Project Structure

```
start-portal-htmx/
├── README.md
├── index.html          # Main HTMX-powered dashboard
├── LICENSE
├── .gitignore
└── docs/               # Future architecture notes
```

## Next Steps

- Add more HTMX interactions
- Introduce a FastAPI backend for real endpoints
- Connect to actual Nexus components (mesh status, agent swarms, etc.)
- Explore HTMX + Alpine.js hybrid if needed

See the main repositories:
- [NexusSpace](https://github.com/digitaldesignerjazz/nexusspace)
- [Start Portal (static)](https://github.com/digitaldesignerjazz/start-portal)

---

**The goal**: A clean, powerful, and maintainable dynamic dashboard for the entire Nexus using the simplest possible tools.