# 🐉 The Dragon's Nest

**Live site → [the-dragons-nest.netlify.app](https://the-dragons-nest.netlify.app/)**

A campus map for Drexel students that actually helps you decide where to go. Regular campus maps just show buildings. The Dragon's Nest shows what each spot is good *for right now*: whether it's a quiet study space, if there's food nearby, if it's indoors or outdoors, and whether it's open late.

> The source code is in a private repo since this was a team class project. Happy to walk through it or share access on request.

---

## What it does

- **Interactive map:** custom pins for campus locations on the Google Maps JavaScript API
- **Filters:** narrow things down by category (academic, study, leisure) and attributes like open late, food, indoor/outdoor
- **Locations page:** every spot as a card, with detail pages for places like Korman, the Library, Rush, and CCI
- **Search:** find a place fast instead of scrolling the map
- **Feedback page:** students can leave comments, stored in Firebase
- **Crowd meter:** a quick read on how busy a spot is

## What I built

I was one of four developers on the team. My main pieces:

- **Search:** built the search bar and results page, then polished the styling and behavior
- **Comments / Feedback:** designed the comments page and connected it to Firebase so feedback actually saves
- **Typography & design system:** built the Typography page that documents the site's fonts, styles, and design choices
- **Crowd meter:** added the busy-ness indicator for locations
- **About & Contact:** combined the About Us and Typography sections and reworked the Contact page
- **UI polish:** hover effects, header fixes, and styling across the location detail pages

## Tech stack

HTML · CSS · JavaScript · Google Maps JavaScript API · Firebase · Supabase · Netlify

## Team

Built as a team project at Drexel University with:

- Yizi Ma
- Andrea Santos
- Angel Santiago
- Wasif Islam
