# Guardian Princess

## Pros

- ~~Has Thorns I by default (even without armor)~~
- Can shoot laser like the guardians
- ~~Inflict weakness II for 2 seconds when hitting an entity~~
- ~~Can breathe/mine/see underwater (base origin)~~
- Not attacked by guardians
- ~~Doesn't get the mining fatigue effect from the elders~~

## Cons
- Spawn in a new water-based dimension (possible with datapack)
```JSON  
{
  "type": "origins:modify_player_spawn",
  "dimension": "better_origins:<name of the dimension>",
  "dimension_distance_multiplier": 0.125,
  "spawn_strategy": "center"
 }
```
- Possibly spawn in an ocean monument?
```JSON
{
  "type": "origins:modify_player_spawn",
  "dimension": "better_origins:<name of the dimension>",
  "structure": "minecraft:ocean_monument",
  "spawn_strategy": "center"
}
```
- Has to find an item in order to get out of the dimension
    - If the item is used in the overworld, can go back into the dimension
    - (I have to choose the item to use)
- ~~Cannot breathe on land (base origin)~~
- ~~Has blindness on land, unless the player has a sea lantern in off-hand~~
- ~~Can only eat aquatic flora (algae, sea weed, corals, sea cucumbers...)~~
- Cannot wear leggings and boots, & cannot wear less than iron