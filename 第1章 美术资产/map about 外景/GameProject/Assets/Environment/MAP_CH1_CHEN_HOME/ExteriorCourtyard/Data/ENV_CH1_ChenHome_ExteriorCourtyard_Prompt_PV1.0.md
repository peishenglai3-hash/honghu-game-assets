# ENV_CH1_ChenHome_ExteriorCourtyard Prompt PV1.0

## 主场景生成

Use case: historical-scene  
Asset type: production-ready game environment master for a pixel RPG map, `MAP_CH1_CHEN_HOME` exterior courtyard area.  
Input image: Image 1 is a style reference only for crisp pixel-art rendering, three-quarter top-down camera, subdued historic colors, material detail, and restrained cinematic lighting. Do not copy its room layout or characters.  
Primary request: Create the exterior courtyard immediately outside Chen Jinan's modest family home in Daijiachang, Hubei, on the morning of September 3, 1927. This is a small playable transition space, not a village panorama.  
Scene: compact tamped-earth courtyard, weathered earth-and-old-brick wall, practical aged wooden gate, damp wall-base stains, sparse weeds, worn footpaths, simple low threshold, and off-frame tree shadows. Show only a short sliver of dirt path beyond the gate.  
Gameplay anchors: clear 96×96-equivalent liaison standing area outside the wooden gate; distinct 144×96-equivalent wall-shadow conversation pocket; unobstructed walkable route using 48 px modules; readable wooden gate with closed, slightly ajar, and narrow-gap states.  
Architecture: literate but not wealthy rural household; plain, functional, worn; no landlord-mansion details; period-appropriate 1927 rural Hubei materials.  
Style: crisp high-detail pixel art / HD-2D narrative RPG, visible pixel clusters and hard pixel edges, low-saturation earth yellow, gray-brown, dark moss green, cool blue-gray shadows, restrained warm doorway light.  
Composition: wide 16:9, 1664×936 target, fixed three-quarter top-down view, readable collision boundaries, courtyard fills most of frame.  
Characters: none; player and NPCs spawn at runtime.  
Avoid: UI, markers, arrows, labels, watermark, modern objects, electric lighting, concrete road, elaborate village background, indoor furniture, fantasy elements, blur, painterly rendering, photorealism.

## 地面底板生成

Use case: precise-object-edit  
Asset type: `L01_GROUND` base plate.  
Edit target: generated courtyard master.  
Change only: remove every wall, roof, gate, door, tree, plant, prop and structure; fill removed areas with continuous compacted-earth courtyard ground matching the central ground texture and perspective.  
Preserve: framing, camera, crisp pixel density, subdued historical palette and early-morning lighting.  
Avoid: structures, props, people, text, UI, markers, watermark and blur.

Generation path: built-in ImageGen.  
Prompt version: `PV1.0`.  
Date: `2026-08-11`.
