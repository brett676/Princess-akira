# Princess Akira and the Missing King

A 33-page choose-your-path pony adventure. The King has been kidnapped by
Princess Akira's brothers, B and B, and every page is a moral or
psychological dilemma. Wise choices bring Akira 2 leagues closer to the
King; unwise ones let B and B carry him 1 league further away. A player
choosing at random wins about 40% of the time.

## Files

- `index.html`: the whole game (HTML, CSS and JS in one file, no build step).
- `vercel.json`: serves the game at both `/` and `/game`.

## Deploying on Vercel

Import this repo at vercel.com/new and click Deploy. Framework preset
"Other", no build command, no output directory. Every push to `main`
redeploys automatically.

To use it at loveakira.com/game, keep LoveAkira.com where it is and add a
redirect from its `/game` page to this Vercel site, or add a subdomain such
as `game.loveakira.com` to this Vercel project under Settings, Domains.
