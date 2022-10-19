# LeafletFileLayer_to_react


Create a custom component where load leaflet file layer library loads after installing and importing it along with togeojson library.

Therefore install and import the two libraries

import togeojson from 'togeojson'

import fileLayer from 'leaflet-filelayer'


call fileLayer(null, L, togeojson) to be able to use L.Control.fileLayerLoad (Source)

Then create the component as you see it on the official library and place the logic under a useEffect


Use the component like this

 <MapContainer ...>
    ...
    <LeafletFileLayer />
 </MapContainer>
