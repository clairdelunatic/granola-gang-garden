---
{"dg-publish":true,"permalink":"/co-s-2026/codex/locations/barovia-land/","title":"Barovia (Land)","dg-note-properties":{"title":"Barovia (Land)","layout":"layouts/base.njk","world":"CoS EloyVera","campaign":"Curse of Strahd","status":"active","system":"5.5e","type":"place","map_height_y":1642,"map_width_x":2048,"scale_pixels":408,"scale_pixels_range":1,"mapCalc1":0.0024509803921568627,"aliases":["land of Barovia","Barovia"]}}
---


> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`

```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [Map of Barovia - 8k - No Names - No Special Locations - Without Hex.jpg](/img/user/CoS%202026/a-library/image%20assets/Map%20of%20Barovia%20-%208k%20-%20No%20Names%20-%20No%20Special%20Locations%20-%20Without%20Hex.jpg) ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [6144, 8192]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 450px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 3072 ### To center the map, make this half of the map height.  
long: 4096 ### To center the map, make this half of the map width.  
minZoom: -5.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -3 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.0024509803921568627 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```

In [[CoS 2026/Sessions/001_20260429 Session 1\|Session 1]],
- According to [[CoS 2026/Codex/NPCs (Friends)/Jander Sunstar\|Jander Sunstar]], [[CoS 2026/Codex/Locations/Barovia (Land)\|Barovia]] has three main towns, each with a shrine to [[CoS 2026/Codex/Factions/Morninglord\|Morninglord]]. These shrines are sacred ground, which protects them from [[CoS 2026/Codex/NPCs (Friends)/Strahd von Zarovich\|Strahd]].
- This land does not appear on any maps.
- It is somehow connected to the mists.
- People do not return from [[CoS 2026/Codex/Locations/Barovia (Land)\|Barovia (Land)]].

## Factions

| Faction                                         | Description                                                   |
| ----------------------------------------------- | ------------------------------------------------------------- |
| [[CoS 2026/Codex/Factions/Vistani\|Vistani]] | Mysterious tradespeople who travel between Barovia and Faerûn |

{ .block-language-dataview}
