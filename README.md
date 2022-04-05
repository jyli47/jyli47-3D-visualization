# UBC Sailing Forward
![IMG_3076-min](https://user-images.githubusercontent.com/97953213/161471963-d3c465ed-1240-411a-8c2a-2fa462d3dcfd.JPG)

[Link To Map: Immersive Reality Visualization](https://jyli47.github.io/jyli47-3D-visualization/ImmersiveReality2.html)

For lab3, I chose vector data ubcv_trees.geojson and ubcv_buildings.geojson, Image vancouver-area-dem for the base map dataset.  Using Qgis2three.js, I generated 2D trees, buildings, and Vancouver Dem layers and clipped them as general six-sided polygon features on UBC Campus Area. Then I created 3D gltf-model and exported it to ImmersiveRealityglb.glb file. Be able to style up some of my own data within an insightful and relevant visual context. 

To visualize the map as 3D gltf-model, I imported it to A-Frame. It shows the UBC 3D gltf-model sailing forward on the ocean with a sphere light on the route in the scene.

The most difficult part for of this lab was the a-entity 3D glft-model loading in the scene. The successful way is use URL directly, showing in the ImmusiveRealtiy.html. Another important thing I have learned was about relative position+ grouping entities in the Introduction to immersive & 3D via A-Frame.


Date Sources:

UBC Open datasets

Past Assignment: Simple bridges between 2D GIS and 3D visualization


Lab3 Immersive Reality Visualization

Jyli47-3D-visualization @jyli47

Cartographer: Jingyuan Li
