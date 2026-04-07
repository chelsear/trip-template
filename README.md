# Trip Guide Template

A clean, editorial travel guide template. Fork this for each new trip.

## Quick Start

1. Click **"Use this template"** → Create new repository
2. Name it `city-trip-YYYY` (e.g., `lisbon-trip-2026`)
3. Clone and edit `index.html`:
   - Update dates and city name in hero
   - Fill in your accommodation details
   - Add your daily schedule
   - Curate your restaurant picks
4. Deploy: `npx vercel --prod`

## Structure

```
index.html   ← All your trip content (edit this)
styles.css   ← Design system (usually don't touch)
```

## Sections

- **Your Neighborhood** — Where you're staying, walk times, nearby spots
- **Daily Schedule** — Day-by-day options with morning/afternoon/evening
- **Dining** — Restaurants, cafes, bars

## Tag Classes

Use these in your schedule for color-coded activities:

| Class | Use for |
|-------|---------|
| `concert` | Music, shows |
| `culture` | Museums, tours |
| `art` | Galleries, exhibitions |
| `wellness` | Yoga, spa |
| `workshop` | Classes, cooking |
| `aperitivo` | Drinks, happy hour |
| `dining` | Restaurants |
| `nightlife` | Clubs, late night |
| `social` | Meetups, events |

## Deploy

```bash
npx vercel --prod
```

First time? It'll ask you to link/create a project. After that, just run the command to update.
