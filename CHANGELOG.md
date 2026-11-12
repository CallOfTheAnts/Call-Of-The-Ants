# Changelog

Version numbers are **big release . stable build . test build**:

- **Big release** (first number): a large change to how the game works, like the GPU and gene update (2.0).
- **Stable build** (second number): a tested, balanced build. The next one is 2.1.0, once the new balance is locked in.
- **Test build** (third number): goes up with every update while things are still being tested and tuned.

The version you're playing is shown at the bottom of the settings panel, where "What's new" opens this list.

## 2.0.2 (test build)

- The changelog can be read in the game: "What's new" at the bottom of the settings panel.
- The ant pictures in the panels are drawn in the background, so they can't hold up the simulation.

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
- Soil fertility: grazing wears the ground out, and food that rots on the ground makes it richer, mostly in quiet places nobody grazes. Plants on rich soil grow bigger and spread. Nests barely enrich their own ground.
- Food that lies around rots: seeds and food left by a dead nest now rot too, just more slowly.
- Farming: strong seed eaters plant grass patches, strong sweet eaters tend aphid trees, and fungus farmers keep a garden that feeds them through winter. Farms go to the best soil in reach, so they move outward as the ground near the nest wears out. A farm whose nest is gone, or that nobody harvests, withers away.
- Ways of living: fast, far-ranging ants eat more; slow, steady, energy-efficient ants last longer on less.
- Niches: specialists gain more from their food, nests with the same diet fight sooner while different diets live side by side, and new colours are more likely where the ground differs from home.

### Other
- Hyperspeed keeps running at full speed when the game is in a background window.
- Developer balance test: Ctrl+Shift+L runs three worlds and shows the results on top of the map, including nest levels, merges and soil.

## 2.0.0

The GPU and gene update. The whole simulation moved onto the graphics card, and colonies started to evolve.

### Runs on the graphics card
- The simulation runs through WebGPU, so far more ants and much bigger maps run smoothly. Browsers without WebGPU get the 1.0 version as a fallback.
- Hyperspeed runs as fast as the graphics card allows.

### Genes and evolution
- Every nest has 16 genes, such as Speed, Defense, Bite, Carry, Energy, View distance and Digging. They mutate when a nest is founded and every few hundred births.
- Raising one gene lowers another, so nests have to trade one strength for another.
- At 160% a gene unlocks an ability, like Crushing jaws, Raiders, Twins or Midday foragers.
- Nests that drift far enough from their colour break away as a new colour.

### Climate and food
- Worlds have climates and biomes: hot and cold ground, deserts, jungles, tundra, swamps, lakes and mountains.
- Each nest likes its own temperature, and ants burn more energy on ground that's too hot or too cold.
- Many kinds of food: seeds, greens, leaves, fruit, nectar, honeydew from aphids, cactus, insects and prey. Each colour learns its own diet, from seed harvesters and fungus farmers to hunters and scavengers.

### Colonies and the world
- Queens walk out with a few workers to found new nests, and colours go to war and lay siege to each other's nests.
- Choose your world: a random map, a map loaded from an image, or one you paint yourself.
- A tutorial for the first time you play.
- Nest panels with genes, climate and food, abilities, mutation history and activity, plus an overview of every colour's genes, climate and size.
- An event log with the big moments: new colours, wars, deaths and abilities.
- An Experimental tab, with features chosen from Instagram comments, starting with the casino.

## 1.0.0

The first version, then called Ant Colony Grid. It ran on the processor, in any browser, on desktop and phone.

- Ants lay scent trails: blue home trails, orange food trails and red battle markers. Busy routes light up, and trails that lead nowhere fade away.
- Plants drop food pellets, food trees appear now and then, and big red beasts wander in that bite back but leave a pile of meat when killed.
- Rival colour families start in the corners, raid each other's nests, fight, and share spare food with allies.
- Nests breed while they have food saved up, and send out founders to start new nests when they grow big or full.
- Random terrain from layered noise: rock ants can't cross, and rough ground that slows them down and wears into roads on busy routes.
- Draw and erase walls to see the ants find a new way.
- Follow a single ant, or tap a nest to see its stats.
- Hyperspeed that stops on chosen events, an event log, map screenshots, and presets to save and load every setting.
- Almost every rule of the world can be changed in the settings.
