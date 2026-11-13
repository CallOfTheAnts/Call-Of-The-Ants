# Changelog

Version numbers are **big release . stable build . test build**:

- **Big release** (first number): a large change to how the game works, like the GPU and gene update (2.0).
- **Stable build** (second number): a tested, balanced build. The next one is 2.1.0, once the new balance is locked in.
- **Test build** (third number): goes up with every update while things are still being tested and tuned.
- **Fix** (optional fourth number): a small fix to a test build's features, like 2.0.3.1.

The version you're playing is shown at the bottom of the settings panel, where "What's new" opens this list.

## 2.1.4 (test build)

- Watch the giants: when one arrives, the camera flies to it, zooms so it fills most of the view, and follows it around until it dies or leaves. Drag the map to look elsewhere, and "Watch the giant" in the World section of the overview to go back to it.

## 2.1.3 (test build)

- Giants turn the way big animals do: by walking an arc no tighter than a circle about a third of their length across, so the whole body swings round its middle instead of pivoting on the snout. Around a nest they now prowl in wide loops.

## 2.1.2 (test build)

- Giants are twice as big: about a fifth of the map long.
- Giants are much harder to kill. Their thick hide makes each ant bite count for little, so it takes a big fight to bring one down, and they bite back harder. A "Giant toughness" slider in Settings sets how hard.
- Every ant eats from a carcass now, not only scavengers, and there is one bite of skin and one of muscle per 2x2 block of tiles instead of per tile, so a carcass is stripped much faster.
- Bones stand like a small mountain ridge: once the carcass is picked clean, ants can't walk through them, except nimble ones (Traversal or Agility of 135% or more), which climb over. The bones are lit and cast a shadow. When only 30% of their wearing away is left, they are low enough for every ant to cross again.
- Summon a giant three ways: the "Summon a giant" button in the World section of the overview, the Giant tap tool in Experimental (it walks in toward where you tap), or the lizard, anteater and bird buttons under Food skills.

## 2.1.1 (test build)

Giant creatures, the first test of what will become 2.2.0.
- Very rarely, a giant walks onto the map: a monitor lizard, an anteater or a bird, each about a tenth of the map long, in one of three colourings (olive, teal or yellow lizards; grey, golden-vest or russet anteaters; hornbills, vultures or eagles). On average one comes every 10 sim hours, anywhere from 5 to 15.
- It walks on from the edge nearest a big nest, crosses anything except water, and prowls from nest to nest eating ants. It bites whatever ants it reaches and attacks now and then: the lizard whips its tail, the anteater lashes out its tongue, the bird pecks.
- Ants can fight back. It takes a lot of ants a long time to bring one down, and a health bar shows how it is going.
- It leaves when the ants on the map have dropped to half of what they were when it came, walking off the nearest edge.
- When it dies it falls over and its body becomes the ground: every tile of it is carcass food, skin on top and muscle underneath, which scavengers carry off one bite at a time, and its weight presses a hollow into the ground the shape of its body. What nobody eats rots slowly.
- Once it is picked clean (or after 8 sim hours) the bones stay as part of the ground for 20 sim hours. They pale to grey, crumble outward and sink into the soil, which grows richer under the carcass the whole time.
- Settings, under Food skills: switch giants on or off, set how often they come, and summon a lizard, anteater or bird right away to try it.

## 2.1.0 (stable build)

The balance from the 2.0 test builds is locked in: the food web, careful colonies, world events, adapted starting nests and uncapped colours from 2.0.14 and 2.0.15 are now the stable base. Same game as 2.0.15.

## 2.0.15 (test build)

- No more cap on colours: up to 61 colours can live at once (was 21), plus gold, silver and bronze from the casino. The "Most colours" slider in Limits now goes all the way to "no limit", which is the default. Colours past the first 24 also vary in lightness so they are easier to tell apart, and each gets its own name.
- The four world choices at the start each have a small icon.

## 2.0.14 (test build)

A big ecosystem pass: food now flows from plants to plant eaters to hunters and back into the soil, and every world gets its own threats.

**Prey that can run out (the fox and rabbit cycle)**
- Live prey now breeds where plants grow and gets scarce where hunters catch most of it. A hunter colony that takes everything around it empties its own hunting ground, goes hungry and shrinks, and the prey comes back once the pressure is off.
- Prey also grazes a little on wild plants where it is plentiful, so gatherers that strip the land bare also starve the prey that hunters live on.
- The overview shows how much prey the land holds on average.

**Careful colonies**
- A new taste next to the other likes: care. Careful colonies leave prey alone where it has grown scarce, and wild plants alone where the soil is worn out, so the land can recover.
- Care grows over generations in colonies whose own food is running out, and fades where food is plentiful. Shows up as "careful" on a nest's page.

**Starting nests fit their home**
- The first colonies of a world lean toward the food that grows around them, cope with a wider range of temperatures, get extra food on poor land, and get small gene nudges for cold or hot homes. Fewer early collapses, and different realms start out different.
- When the ground gets warmer or colder than a nest likes (seasons, droughts, the temperature setting), its liked temperature now follows much faster, so species re-adapt to a changed climate.

**World events: one or two per world**
Each new world picks one or two of these at random. Each one exists to push evolution somewhere:
- 🕷 Spiders spin webs near food. Brave, strong-biting colonies tear them down and eat the spider; ants with good eyes walk around them; careless ones get caught.
- ⏳ Antlions hide pits in sand, desert and beaches. Only ants with good eyes see them in time.
- 🐦 Birds hunt ants on open ground and can't be fought. Rough ground and rock give cover.
- 🐟 Fish get stranded on the shore: rich food for hunters that settle near water.
- 🌊 Floods in some springs hit nests close to water, then leave the shore extra fertile.
- 🔥 Wildfires sweep across hot, dry land in summer. The ash makes the soil rich afterwards.
- 🦠 Disease spreads between big, crowded nests of the same colour. Health resists it, so no single species can fill the map.
- 🦗 Locust swarms cross the map, stripping plants and leaving a feast of dead locusts for hunters and scavengers.
- 🐞 Ladybugs eat aphids. Unguarded aphid trees dry up; herders with strong Bite and Courage chase them off.
- ☀ Drought years: green plants and fruit wilt while seeds, cactus and lichen hold on, and the ground feels hotter.
- The new "World" section of the overview lists this world's events, what each one is for, what is happening right now, and how many ants live each way of life.
- Settings, under Food skills: switches for prey that can run out, adapted starting nests and world events, plus "Always include" to make sure the next world has a certain event.
- The map can now hold eight beasts, webs, pits and birds at once (was four).

**Four realms test map**
- "Four realms" is now a choice when you pick a new world: a mountain cross splits the map into cold and dry, hot and dry, cold and damp, and hot and damp land, with six passes between them.
- The balance test (Ctrl+Shift+L) now runs the four realms first, then two random worlds, and reports the world events, the prey, and which ways of living each quarter of the map ended up with.

## 2.0.13.1 (fix)

- Abandoned tunnels are gone within about 3 hours: dug ground grows back 25% of the way every 15 minutes (was 5%). Tunnels in daily use are still dug faster than they grow back. The slider goes up to 50%.

## 2.0.13 (test build)

- No more X-shaped tunnels: queens walking to a new home and war parties marching on a rival no longer dig on the way. Their long, straight walks between nests were carving lines across the whole map.
- Ground grows back faster: 5% of the way every 15 minutes by default (it was 1%, which brings back only about a third in 10 hours). The slider now goes up to 20%.
- More visible evolution: mutations after births are half the founding size instead of a third, and come every 150 births instead of 200. Body parts start to show from 105% (were 112%), are fully grown at 135% (were 160%), and reach their extreme form near 200% (were 250%), so drifting colours look different much sooner.

## 2.0.12 (test build)

Aphid herders won almost every run, and every colony ended up with the same long nectar straw.
- Aphid herding is weaker: a nest looks after at most three trees (one, plus one per 80 ants) instead of every aphid tree in reach, plants new ones half as often, and a tended tree drips 35% more instead of 70% and lasts a third longer instead of twice as long.
- The nectar straw is shorter and thinner, starts later (at 36% sweet food skill instead of 28%) and is only full length for real sweet specialists. The weevil snout comes later too.

## 2.0.11 (test build)

- The family tree has its own "Family tree" section in the overview, and a "full screen" button that opens it in a big window (Esc or a click outside closes it).
- The tree stays readable as it grows: a colour that died out, along with its whole line, is folded away. Sister colours that all died out share one small "+N died out" chip under their parent; click it to show them, and "fold" to hide them again. A dead colour that still has living descendants stays visible, as a smaller card.
- New colours appear even less often: 10% of new nests start a new colour, down from 20%.

## 2.0.10 (test build)

- Ants still died early, so the ground is back to how it was before 2.0.5: the original roughness and slowdown (1/3 speed at its worst). The new tunnel look, the faster digging on busy routes, chambers and ground growing back all stay.
- The History section is now a real family tree: each colour is a card with a picture of its ant (as it looked at its biggest), joined by lines to the colour it came from and the colours that came from it. Hover a card for its details; dead colours are faded with a dashed border, metal ones glow. Wide trees scroll sideways.

## 2.0.9 (test build)

- Dug ground grows back: 1% of the way to its natural state every 15 minutes, and spoil heaps settle the same way. Tunnels in use are dug faster than they grow back, but those of a dead nest slowly fade. New setting: "Ground grows back".
- From the 2.0.8 balance test, where all three worlds shrank to 2 or 3 nests: ground roughness is back near its natural level (the 1/4 slowdown stays, so tunnels still pay off), since the rougher ground of 2.0.5 slowed every trip by about a third.
- Queens are less picky about mountains and water: they give up on their taste sooner and settle, instead of walking far and dying on the way.

## 2.0.8 (test build)

- New colours appear less often: the chance a queen starts a new colour is 20% instead of 35%, and even on very different ground it tops out at 60% instead of 90%.
- Metal colonies (gold, silver, bronze) keep their colour when they spread. They only become a new colour by drifting too far from their family, and then they keep their metal shine in the new colour, and so do their descendants.
- History: a new section in the overview with a family tree of every colour that ever lived, under the colour it came from. Each shows when it lived, its biggest size and way of living, and how it began (first colours, a queen on new ground, breaking away, or the casino). Colours that died out are crossed out; clicking a living one opens its biggest nest.

## 2.0.7 (test build)

From the 2.0.6 balance test: one world did well (16 nests, raiders appeared), but another fell to 2 nests, and food stayed scarce around nests.
- Plants only wither on really worn-out soil now (below 70% fertility instead of 90%), so lightly grazed ground near a nest keeps its plants. Below 80%, plants still use themselves up faster.
- Grazing wears the soil a bit more slowly.

## 2.0.6 (test build)

Fixes from the 2.0.5 balance test, where worlds starved badly (one fell to 2 nests and 90 ants) and only 2 or 3 ways of living showed up.
- Crowded niches are measured against the map's own mix. Before, when nearly every nest lived the same way, every nest lost a third of its food at once. Now the average nest keeps 100%, and only ways of living more common than usual lose out (down to 70%), while rarer ones gain (up to 125%).
- Rough ground is a bit easier: 1/4 speed at its worst instead of 1/6, and a little less rough overall. Tunnels still pay off clearly.
- A new nest starts in a small dug-out hollow, so it isn't stuck in rough ground before its tunnels exist.

## 2.0.5.1 (fix)

- Metal nests were too strong. Their 3 to 5 strong genes are now 150% instead of 200% or more, the smaller lucky changes are gone, and they get half as many weak genes (rounded down) at 50%: for example 4 strong and 2 weak, or 3 strong and 1 weak.

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
