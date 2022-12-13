# fivem-map
 
#### Installation
1. Drag and drop the map resource in your standalone folder
2. Make sure this starts before your hud resource

#### Images of map
(https://imgur.com/BlY0b1S, https://imgur.com/PCGZwi6)


# Hud/Map Issues
If your having having hud and map flickering issues. 
#### QB-Hud
if using QB-Hud go to client.lua and search -- Minimap update (Should be around line 1017)
Change this SetRadarZoom(1000) to be SetRadarZoom(1100) And that should fix your problems 

#### PS-Hud
if using PS-Hud go to client.lua and search -- Minimap update (Should be around line 1208)
Change this SetRadarZoom(1000) to be SetRadarZoom(1100) And that should fix your problems 
