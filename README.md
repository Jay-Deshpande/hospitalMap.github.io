# Map of Major Hospitals in Colombo, Sri Lanka

https://jay-deshpande.github.io/hospitalMap.github.io

I originally wanted to include the entirety of Sri Lanka in my geographic analysis of hospitals and green spaces but the amount of tiles necessary is staggering so I decided to limit my area to Sri Lanka's Capital: Colombo. One of the factors that drove this decision was my need for high levels of zoom. This is because most of the hospitals and green spaces and pedestrian/bicycle walkways are relatively small. Specifically, the overall map has a minimum zoom level of 3 and a maximum zoom level of 16. Each tileset has a maximum zoom of 16 to match the overall map. However, the minimum zoom extent of each tileset is less than the overall map's minimum zoom. This is because each tileset was captured from a small canvas extent surrounding Colombo. I still include a universal basemap from CartoCDN to retain a semblance of continuity between my specific map and the broader geographic context. This way the user can zoom out very far and not have a totally diminished experience.

## Tileset 1 Basemap

This is a monochrome basemap that is designed to be minimalistic and allow thematic layers to pop. <img width="769" alt="Screen Shot 2021-02-26 at 5 24 18 PM" src="https://user-images.githubusercontent.com/6693037/109369919-9e697300-785b-11eb-8f0d-6ba967c4a067.png">


## Tileset 2 Hospital Locations

This is a thematic layer made of hospital locations in Colombo. Hospitals are denoted by a red cross. This layer is completely seperate from all of the others, but the image I included displays the locations on top of the basemap for context. <img width="771" alt="Screen Shot 2021-02-26 at 5 25 02 PM" src="https://user-images.githubusercontent.com/6693037/109369936-a7f2db00-785b-11eb-91eb-fa4738443b02.png">


## Tileset 3 Hospital Routes

This tileset displays the major roads and highways leading to the marked hospitals. <img width="769" alt="Screen Shot 2021-02-26 at 5 24 31 PM" src="https://user-images.githubusercontent.com/6693037/109369938-ac1ef880-785b-11eb-95d6-757032626021.png">


## Tileset 4 Green Space Comparison

This tileset offers a comparison between structures like roads and buildings and green open spaces like parks, golf courses, fields, bicycle paths, pedestrian walkways etc. Structures are colored black while open spaces are colored green. This map is most helpful when the user zooms into a specific area that they want to analyze. This is because there are relatively few open spaces and they tend to be small. Colombo is a large metropolitan city so it makes sense that structures greatly outnumber green spaces. <img width="768" alt="Screen Shot 2021-02-26 at 5 24 44 PM" src="https://user-images.githubusercontent.com/6693037/109369944-b04b1600-785b-11eb-88f8-e96839260ea3.png">
