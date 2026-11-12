# Changelog

Version numbers are **big release . stable build . test build**:

- **Big release** (first number): a large change to how the game works, like the GPU and gene update (2.0).
- **Stable build** (second number): a tested, balanced build. The next one is 2.1.0, once the new balance is locked in.
- **Test build** (third number): goes up with every update while things are still being tested and tuned.

The version you're playing is shown at the bottom of the settings panel.

## 2.0.1 (test build)

### Ants look the way they've evolved
- Every nest's ants are drawn from one body that grows and blends with the nest's genes, so colours look clearly different from each other.
- A mild gene change adds a part: crab pincers, an extra body segment, a stinger, wings, feathered antennae, a third antenna, padded feet, a double abdomen, a shovel head and more.
- Pushed much further, the whole body shifts. Bite and Defense close the body into a beetle with wing cases and stag antlers. Health and Steadiness stretch it into a centipede, or a pill bug with heavy armour. Other extremes: scorpion tail, earwig forceps, wasp waist, dragonfly wings, dome eyes and eye stalks, queen belly, firefly lantern. Hunters grow trap jaws and mantis arms; sweet eaters grow a nectar straw and then a weevil snout.
- Changes are smooth: after a mutation the ants grow into their new shape over a couple of seconds. A new nest starts out looking like its parent.
- Casino colours get a metal finish: banded tones, a sharp glint, a warm edge light and the odd sparkle.
- The overview's gene tab shows the average ant of the three biggest colours.

### Nests
- No fixed limit on the number of nests by default.
- A queen that settles close to a nest of her own colour joins the oldest one instead of starting a new nest. That nest goes up a level (up to 5): each level holds half again as many ants and as much food, and needs more ants before it sends out queens.
- Small, younger same-colour neighbours move into the older nest over time, ants, food and farms included.
- Colours with many nests send out queens less often.
- An area can hold only so many nests of any colour (6 by default). A queen that finds it full goes home.
- Each nest's food store has a limit that grows with its level.
- Nests show one extra ring per level on the map. New settings: "Nests merge" and "Nests in one area".

### A living world with niches
- Seasons: a year every 40 minutes. Plants grow fast in summer and slowly in winter, and the ground feels warmer or colder.
- Soil fertility: grazing wears the ground out, and food that rots on the ground makes it richer. Plants on rich soil grow bigger and spread.
- Food that lies around rots: seeds and food left by a dead nest now rot too, just more slowly.
- Farming: strong seed eaters plant grass patches, strong sweet eaters tend aphid trees, and fungus farmers keep a garden that feeds them through winter. Farms go to the best soil in reach, so they move outward as the ground near the nest wears out. A farm whose nest is gone, or that nobody harvests, withers away.
- Ways of living: fast, far-ranging ants eat more; slow, steady, energy-efficient ants last longer on less.
- Niches: specialists gain more from their food, nests with the same diet fight sooner while different diets live side by side, and new colours are more likely where the ground differs from home.

### Other
- Hyperspeed keeps running at full speed when the game is in a background window.
- Developer balance test: Ctrl+Shift+L runs three worlds and shows the results on top of the map, including nest levels, merges and soil.

## 2.0.0

The GPU and gene update: the simulation runs on the graphics card through WebGPU, with genes, mutations, colours, abilities, climate, diets, wars, founders, the world chooser, the tutorial and the casino.
