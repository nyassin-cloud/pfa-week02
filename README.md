My tool is a weather generator for Maya. It started as a falling snow tool using an uploaded image, with controls for amount, size, area, and speed. I expanded it to create rain, ash, dust, leaves, storms, thunderstorms, fog, and sandstorms. The weather can interact with objects already in the scene: snow, ash, and dust can build up on surfaces, while rain can create splashes and growing puddles. Users can also adjust the weather area, particle shapes, wind, and turbulence. Each weather effect creates a separate animation layer, allowing multiple effects to play together.
how to run:
1. Download the repository and open Maya.
2. Open Windows → General Editors → Script Editor and choose a Python tab.
3. Open `weather_studio.py`, select the entire script, and execute it.
4. Choose a weather tab and start with a small particle count.
5. To use scene collisions, add polygon objects and configure the collision controls.
6. Build the effect and play or scrub the timeline.
7. Rebuild after changing the scene, weather settings, or baked animation range.
