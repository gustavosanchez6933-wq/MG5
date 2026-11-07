# MG5
## Devlog
1. I think it's more advantageous for NavMesh VS. for a large population of NPC like a village full of NPCS. In games like Red Dead Redemption 2, many of the NPCS have a NavMesh to walk around the town in a set path. It's definity be much more work if you have to code each individual NPC with their own character's movement with physics. However, im platform games such as Sonic the Hedgehog or Super Mario, scripting the player’s movement with physics is much more advantageous since it gives the player more precise controls and Sonic is all about speed and physics so giving Sonic physics makes the player feel his speed.

2. After I fixed the for loop in BirdManager.cs, using the if statement of (Vector3.Distance(bird.transform.position, _player.position) <= _interactDistance), it tells Unity where's the current position of the bird and it's new positon after moving (transform), tracks where the player's current position, and then use the <= _interactDistance to make the birds run away if the distance is less than or equal to the distance of the player. Lastly, bird.RunAway(_player.position); tells the birds to run away after it's distances towards that _player.position is less than or equal to _interactDistance.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
