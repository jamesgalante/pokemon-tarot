# Pokémon Tarot

A tarot reading dealt from actual vintage Pokémon cards. Think of a question, deal
three cards — **Past, Present, Future** — and flip them over. The interpretation is
up to the reader.

**Play it here → https://jamesgalante.github.io/pokemon-tarot/**

## How it works

- The base deck is the **original 151 Kanto Pokémon**, each as its earliest vintage
  printing (Base Set → Jungle → Fossil, plus the Black Star promo Mew).
- Toggleable **expansion packs** add real cards from Team Rocket, Gym Heroes &
  Challenge, and the Neo (Johto) sets.
- Each card has a 1-in-3 chance of being dealt **reversed**.
- Each card has a 0.1% chance of being **✨ shiny** — an animated holographic foil.
  (Append `?shiny=1` to the URL to preview the effect.)

## Tech

Two static files (`index.html`, `deck.js`) — no build, no dependencies. Card images
are served by [pokemontcg.io](https://pokemontcg.io); `deck.js` was generated from
its API. Pokémon and Pokémon card images are © Nintendo / Creatures / GAME FREAK /
The Pokémon Company; this is a non-commercial fan project.
