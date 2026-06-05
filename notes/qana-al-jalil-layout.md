# Qana al Jalil Layout v1

Target: Company of Heroes 1 urban 2v2 map.

## Core idea

- A river splits the map into west and east halves.
- Two bridges are the only main crossings.
- Each side has a raised high-ground zone with infantry positions and cannon/emplacement spots.
- The city is dense, with streets, blocks, courtyards, rubble, and narrow side routes.

## Recommended map shape

- Rectangular map.
- Long axis runs north to south.
- River runs vertically through the center, splitting west and east.
- North bridge in the upper third.
- South bridge in the lower third.

## Team layout

- West team spawns on the west bank.
- East team spawns on the east bank.
- Each team gets one north-side spawn and one south-side spawn.

## Top-down sketch

```text
WEST HALF                               EAST HALF

   [W1 Spawn]                            [E1 Spawn]
      \                                      /
       \__ high ground __      __ high ground __
          \           /        \           /
           \  north   / bridge  \  north  /
            \ bridge  /=========\ bridge /
             \_______ / RIVER    \_______/
             /       \           /       \
            / streets  \         / streets \
           /    city    \       /    city   \
          /______________\     /_____________\
       __/  south bridge  \   /  south bridge \__
      /====================\ /====================\
     /        river         X X         river      \
    /_______________________________________________\

   [W2 Spawn]                            [E2 Spawn]
```

## High-ground zones

Each side should have one elevated zone that:

- overlooks at least one bridge approach
- supports infantry
- has a cannon/emplacement pad or flat firing space
- can be flanked from at least one side street

Suggested detail:

- West north high ground: behind the north bridge on the west side.
- West south high ground: behind the south bridge on the west side.
- East north high ground: mirrored version on the east side.
- East south high ground: mirrored version on the east side.

## Bridge defense points

At each bridge end:

- one capture point on the approach road
- one defensive cover cluster
- one vulnerable flank route

Use:

- sandbags
- low walls
- wrecked cars
- broken stone barriers
- garrisonable buildings nearby, not directly on the bridge itself

## Resource plan

Keep resources fair and readable:

- Each team gets one safe fuel point near spawn.
- Each team gets one safe munitions point near spawn.
- Center-side resources near the river should be contested.
- Avoid putting both fuel points on the same side of the map.

## Streets and cover

Urban feel should come from:

- narrow streets
- apartment blocks
- courtyards
- alleyways
- rubble piles
- shell holes
- barricades
- wrecked vehicles

Do not over-open the map. Every major lane should have:

- one main route
- one flank route
- one cover-heavy fallback position

## Build order in World Builder

1. Create the map dimensions.
2. Shape the river and carve the center divider.
3. Place the two bridges.
4. Block all other river crossings.
5. Lay down the spawn zones.
6. Raise the high-ground areas on both sides.
7. Block in the city blocks and streets.
8. Add bridgeside defenses and cover.
9. Place resource points.
10. Test line of sight and movement.
11. Tweak chokepoints and flanks.

## First testing goals

- No spawn can rush both bridges too easily.
- Both bridges are valuable, but neither should completely decide the game alone.
- High ground should be strong, but not impossible to take.
- Infantry should have multiple ways to flank fortified bridge ends.
- Cannons/emplacements should feel useful without dominating the whole map.

## Naming

Map name: `Qana al Jalil`

