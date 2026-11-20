---
version: 1.0.0
last_updated: 2026-11-20
revision_note: "Remake of previous GDD"
---

# Lanting Guard: Rush the River

## Pitch

*Lanting Guard: Rush the River* is a roguelike tower defense game inspired heavily by [Slay the Spire](https://en.wikipedia.org/wiki/Slay_the_Spire), [Clash Royale](https://en.wikipedia.org/wiki/Clash_Royale), [Bloons TD 6](https://en.wikipedia.org/wiki/Bloons_TD_6), and [Plants vs Zombies](https://en.wikipedia.org/wiki/Plants_vs._Zombies). The player traverses a node-based map and defends their [rumah lanting](https://id.wikipedia.org/wiki/Rumah_Lanting) from trash polluting the river by placing [jukung](https://id.wikipedia.org/wiki/Jukung) between waves and supporting them using items such as mud ball and fishing net.

## Core Loop

```mermaid
flowchart TD
	A[Player Enters Room] --> B{Enemy Sees Player?}
    B -->|Yes| C[Play 0.6s Wind-Up Telegraph]
    B -->|No| D[Continue Patrol]
    C --> E[Lunge Attack]
    E --> F([0.8s Recovery Window])
    F --> B
```

## Out of Scope

