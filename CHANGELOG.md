# Changelog

Version numbers are **big release . stable build . test build**:

- **Big release** (first number): a large change to how the game works, like the GPU and gene update (2.0).
- **Stable build** (second number): a tested, balanced build. The next one is 2.1.0, once the new balance is locked in.
- **Test build** (third number): goes up with every update while things are still being tested and tuned.
- **Fix** (optional fourth number): a small fix to a test build's features, like 2.0.3.1.

The version you're playing is shown at the bottom of the settings panel, where "What's new" opens this list.

## 2.0.5 (test build)

### Tunnels and chambers
- Rough ground is rougher and slows ants much more (1/6 speed at its worst instead of 1/3), so a tunnel makes a real difference.
- Ants dig twice as much per scrape and dig most on their runs between nest and food, so their routes sink into tunnels that speed up gathering. The earth is piled up beside the tunnel.
- Tunnels are drawn as dark sunken channels with soft, lit walls, and the dug-out earth shows as pale heaps.
- Chambers: nests with enough ants dig rooms over time, in a ring around the nest and joined to it by corridors, plus a store room beside their best food (a farm, tended tree or food tree). Bigger and higher-level nests dig more. Each finished chamber holds 10% more food.
- New setting: "Chambers". "Ants dig roads" is now "Ants dig tunnels".

### Worn-out soil
- Plants on worn-out soil wither within a few minutes, and use themselves up faster while they last. Farmers have to keep planting or spread their farms onto fresh ground.

### Experimental
- Tap tools in the Experimental tab: place a casino, or a metal nest, where you tap.

### Likes and dislikes
- Every nest has its own tastes, passed on to its new nests with a little change (a new colour changes them more):
- Mountains: some settle close to rock and lean their scouting toward it, others prefer open ground.
- Water: some settle near water, others keep away from it.
- Gambling: some spot the casino from much further away, others never go in or follow its gold trail.
- Company: some queens settle closer to other nests and sooner, others walk further and keep their distance.
- Each colour has one friend it never lays siege to, and one foe it attacks sooner.
- The nest panel lists a nest's strong likes and dislikes, its friend and its foe. New setting: "Likes and dislikes".

## 2.0.4 (test build)

### More ways of living, and none can take over
- Three new ways of living: **Raiders** (take food from rival nests: strong Courage and Bite, or a habit of plundering), **Scavengers** (live off the dead and what others leave behind) and **Gatherers** (live off wild plants without farming). They join Runners, Thrifty, Hunters, the three kinds of farmers and Generalists.
- Crowded niches: a way of living that many ants share gets less out of its food (down to 65%), and a rare one gets more (up to 125%). So when farmers spread everywhere, every farmer nest feels it, and hunters, raiders or scavengers nearby get their chance. Worked out once a minute from all the ants on the map.
- The nest panel shows when a nest lives a crowded or a rare way of life, and how much its food is worth because of it.
- New setting: "Crowded niches", next to "Niches".

## 2.0.3.1 (fix)

### Casino: metal colonies get a fair start
- When the house wins, the casino now blows up first, and the metal colony moves into the empty land the blast leaves behind.
- The casino explosion reaches further (340 tiles instead of 260).
- A metal colony is made for its spot: it likes the exact local temperature, copes with a wider range, and is skilled at the food that grows there.
- It also starts with 3 to 5 very strong genes at 200% or more (from Speed, Defense, Steadiness, View distance, Courage, Health, Carry, Energy and Bite), plus smaller lucky changes, 30 ants and 300 food.

### Overview
- The average ants of the three biggest colours have their own "Ants" section.
- The colour names under the gene chart are gone. On the chart, each colour is drawn as solid as its size: big colours stand out, small ones are faint.

## 2.0.3 (test build)

- Loaded map images draw their mountains exactly where the image puts them (blue near 43 or 213 is a peak, 128 is flat), so a map can have solid mountain walls with gaps as tunnels.

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
