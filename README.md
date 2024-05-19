# Open Fight Pass

The Open Fight Pass is a simple webiste designed to help users
navigate free fighting content on Youtube. The purpose of the
website is to offer the casual MMA enjoyer a UFC Fight Pass
experience, without having to pay 100$/year to enjoy some fights.

## Available services

- UFC 
- ONE
- PRIDE FC
- Pancrase
- Thai Fight
- Max Muay Thai
- Rajadamnern Stadium (RWS)
- WLC
- K1
- RISE
- Karate Combat
- PBC
- GBP

## Architecture

This website uses as [Astro](astro.build) as the base platform, while it uses [Piped](https://github.com/TeamPiped/Piped) to display channel and playlists (since YouTube has iframe protection). I use [bun](bun.sh) as the runtime and package manager for this project.

## Hosting

This website doesn't need SSR and as such can be hosted as a static site with [tons of web hosting service](https://docs.astro.build/en/guides/deploy/). I personally use Vercel because of its free tier.