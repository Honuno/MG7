# MG7
## Devlog
Write your Devlog here. :3
The TreeOfBirds script goes onto the Tree GameObject and makes the sparrows appear whenever the player gets near the tree. It uses an array to hold all the Sparrow objects, except the Sparrow_Start GameObject, which then loops through them every frame so you can easily add or adjust them in the Inspector. To see how close the player is, the script uses Vector3 for the player's spot and each bird's spot, checks the distance between them, and turns nearby birds on when they are within the interaction distance.
## Open-Source Assets
- [Forest Nature Pack](https://kaylousberg.itch.io/kaykit-forest) - environment 3D models
- [Quirky Series](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235) - animal 3D models
