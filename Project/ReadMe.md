#Welcome to Tornado Country!
Game Features:
- Animation
- Textures
- (Downloaded) .gltf files
- custom heightmap made in GIMP
- skybox
- events
- sound effects
- Physics
- Sprites
- Particles
- GUI

How it Works:
- Select two points on the ground mesh
- Watch a tornado tear through the town
- Profit?

Notes:
- None of the artwork or sounds are mine (sources will be at the bottom)
- Coded using babylon.js
- In the settings menu: The top slider is SFX volume, the middle is music volume, and the bottom is master volume
- The one blender model i did make doesnt work for whatever reason. You can see it if you open the Tornado.blend file in Blender
- The constant "MaxMeshes" is the maximum of each mesh thats loaded, not total. It shouldn't excede 14 as thats the number of tree position.
- If you increase "MaxMeshes", adjust the "importMesh()" function to make sure it doesnt go out of scope
- The strength and radius of the vortex can be adjusted in the "createTornado()" function
- The mass of each mesh can be adjusted in the "importMesh()" function

Known Bugs:
- Trying to start a game again by exiting to main menu then pressing start will crash the game
- Tree models clip through the ground

Model Sources:
- [Jaguar](https://sketchfab.com/3d-models/2000-jaguar-xj-sport-x308-xj8-192011ef37994e8ca2f09cd1d73ca166)
- [Mclaren](https://sketchfab.com/3d-models/mclaren-600lt-f576442d6839419ea157837df84ddfee)
- [Japanese House](https://sketchfab.com/3d-models/dae-final-assignment-milestone-house-58a9edfc71ab4adc869061d4e5e862d1)
- [House](https://sketchfab.com/3d-models/house-27f1316691c940e29b2c2280616d0cda)
- [Surf Shack](https://sketchfab.com/3d-models/surf-cabin-e109abb2d1054c82b7e277cf03eae955)
- [Trees](https://sketchfab.com/3d-models/trees-and-foliage-c3423a86515444a2b323d422ac16e710)

Sound Sources:
- [background](https://www.fesliyanstudios.com/royalty-free-music/download/dancing-in-the-desert/1572)
- [Menu](https://www.fesliyanstudios.com/play-mp3/2901)
- [Point](https://www.fesliyanstudios.com/royalty-free-sound-effects-download/video-game-menu-153) (under "Menu Selection Change M")
- [rain](https://mixkit.co/free-sound-effects/rain/) (under "downpour loop")
- [Thunder](https://mixkit.co/free-sound-effects/thunder/) (under "distant thunder explosion)
- [wind](https://mixkit.co/free-sound-effects/wind/) (under "strong wind")
- [Tornado Siren](https://orangefreesounds.com/tornado-siren/)

Image and sprite Sources:
- [Tornado background](https://gooseberry.blender.org/cosmos-laundromat-tornado-concept-art/)
- [Lightning](https://www.seekpng.com/ipng/u2q8q8i1u2t4q8i1_animation-sprite-electric-blue-lightning-game-lightning-animation/)
- I cant find the link for the road map I used but i did google "toy road map" to get it.