# ChronosRift

A fake landing page for a made-up strategy game, built as our first real Tailwind project. Team project with Eric and Pavel — the idea was to design a marketing/pre-launch page for a fictional "real-time strategy meets MOBA hero combat" game and see how far we could push Tailwind's utility classes without writing custom CSS.

## What it is

Static, single-page mockup — no backend, no real login, no game behind it. Everything (Login, Sign Up, "Jetzt Spielen") is a dead link for now. The point of the exercise was the layout and styling, not functionality:

- Transparent nav bar that overlays a hero section, collapses into a mobile menu
- Custom Tailwind theme (`@theme`) with a game-appropriate color palette — yellow/gold accents, faction colors for four in-game factions
- Hero section with stats counters (players, factions, season)
- Content sections describing the (fictional) game concept

Copy is in German since that's how our team worked on it.

## Stack

Tailwind CSS via the browser CDN build (`@tailwindcss/browser`) — no build step, no npm install, just open `index.html`.

## Status / known rough edges

This was an early group project, so a few things are still messy and on my list to clean up:
- `niko_index.html` is a leftover personal working copy sitting next to the real `index.html` — needs to go
- No `.gitignore`, so `.DS_Store` ended up committed
- Only the hero + intro sections are really finished; the rest of the page structure exists but isn't fully styled

## Running it

Just open `index.html` in a browser. No install, no server needed.
