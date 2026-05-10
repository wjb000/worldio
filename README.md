# WorldIO 🌍

**A living, breathing, self-propagating simulated world.**

Users (and AI citizens) live, thrive, build, trade, and grow together in a beautiful browser-based ecosystem. Zero server costs. Runs 100% on GitHub Pages. Fork it, customize it, and propagate your own unique universe across the internet.

> "In the beginning there was code. Now there is WorldIO."

## ✨ Live Demo

**Coming online shortly** — Enable GitHub Pages in repo Settings → Pages → Source: `main` branch, root folder. Then visit:

`https://wjb000.github.io/worldio/`

## Features

- **Real-time Simulation**: Watch a dynamic ecosystem evolve — trees grow, animals roam and hunt, citizens gather resources, trade, reproduce, and build a civilization.
- **You Are the Founder**: Control your avatar. Move, gather, build houses, trade with citizens, shape the destiny of your world.
- **Living Economy**: Resources have dynamic value. Supply & demand shifts as the population grows. Buy, sell, and accumulate wealth.
- **Self-Propagating**: 
  - Export your world state as a shareable JSON snapshot.
  - Import any world snapshot shared by others.
  - Generate unique seeded starting worlds via URL (`?seed=yourcode`).
  - Fork this repo on GitHub → deploy your customized variant instantly on your own Pages.
  - In-world "Explorers" metaphorically spread the idea.
- **Grows Organically**: Population booms, economies develop, seasons change, day/night cycles affect behavior. The world literally gets more alive the longer you (and others) nurture it.
- **Zero Server Cost**: Pure client-side HTML + Canvas + JS. No backend, no hosting bill, ever.
- **Open Source & Extensible**: Easy to hack. Add new agent types, biomes, mechanics, visuals. Pull requests welcome.

## How to Play (Controls)

1. **Move your Founder avatar**: WASD / Arrow keys or click on the canvas to walk there.
2. **Change Tool** (bottom toolbar):
   - **Select/Move**: Default. Click to move.
   - **Gather**: Click near trees/resources to harvest.
   - **Build**: Click to place a House (attracts citizens & stores resources).
   - **Spawn Citizen**: Click to birth a new citizen into the world.
   - **Trade**: Click near citizens to initiate smart trades based on needs.
3. **UI Panels**:
   - Left: Simulation controls (Pause/Play, Speed, New World).
   - Right: Live stats — Population, Resources, Economy Health, Your Wealth, Civilization Score.
4. **Self-Propagate**:
   - **Export Snapshot**: Download full world state.
   - **Import Snapshot**: Load a friend's world file.
   - **Share Link**: Copies a message + repo link for socials (X, Reddit, Discord).
   - **Seed Worlds**: Add `?seed=mycoolworld` to URL for a unique procedural start.

## Vision & Why It Works

WorldIO is designed to be **addictive, beautiful, and viral by nature**:

- People fall in love with "their" world and want to show friends.
- Sharing snapshots or seeds feels like sharing a living pet or colony.
- Forking on GitHub is the ultimate propagation — each fork is a new parallel universe.
- No login, no install, instant fun in any browser.

The more people play, fork, and share, the more the *idea* of WorldIO grows and thrives across the web — exactly like the simulation inside.

## Monetization (Sustainable & Aligned)

WorldIO core is **free & open source forever**. Here's how you (the creator/maintainer) can sustainably make money while keeping the spirit alive:

1. **GitHub Sponsors** (primary): Set up sponsors on your profile. Supporters get early access to new features, special starting seeds, or their name in the world credits.
2. **Crypto Donations**: Display an ETH / SOL address prominently (update in code).
3. **Custom World Commissions**: Offer paid services to build bespoke simulated worlds for:
   - Educational institutions (ecology, economics teaching tools)
   - Brands & marketing campaigns ("grow your brand's world")
   - Game studios (prototype mechanics)
   - Metaverse / Web3 projects (on-chain agent economies)
4. **Future Premium Layer** (optional, non-breaking): Hosted persistent multi-user versions or advanced analytics dashboards (using cheap serverless if needed). Core always free.
5. **Merch / Digital Goods**: Sell beautiful printable maps of famous community worlds, or limited "Genesis Citizen" NFTs (off-chain art + lore).

Because it spreads itself virally with zero marginal cost, even modest sponsorships + a few commissions per month can be very rewarding while the project grows exponentially.

## Tech Stack

- Single-file `index.html` (Tailwind via CDN + Vanilla Canvas + JS)
- Fully client-side, works offline after first load
- Easy to extend: All logic in one readable file

## Getting Started Locally

```bash
git clone https://github.com/wjb000/worldio.git
cd worldio
# Just open index.html in browser (or use Live Server extension)
```

## Roadmap Ideas (Community Driven)

- [ ] 3D version with Three.js (opt-in)
- [ ] Persistent multi-user rooms via URL or simple peerjs
- [ ] On-chain resource tokens (experimental)
- [ ] More agent personalities & emergent storytelling
- [ ] Mobile touch controls polish
- [ ] Procedural music / WebAudio soundscape

## License

MIT — Fork freely, propagate wildly.

---

**Built with love for a more interconnected, playful internet.**

If you grow an amazing world, tag @wjb000 or open an issue with your snapshot. Let's make the multiverse thrive together.

*WorldIO — Live. Thrive. Transact. Propagate.*