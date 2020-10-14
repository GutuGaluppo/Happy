# Happy
App to find the nearest orphanage and change children's day with love donation.

# Intall Icon
npm install react-icons

# Intall React Router
npm install react-router-dom
npm install @types/react-router-dom

# Map
npm install leaflet react-leaflet
npm install @types/react-leaflet

import { Map, TileLayer } from 'react-leaflet'
import 'leaflet/dist/leaflet.css'

...

  <Map
    center={[-23.6823494, -46.7353808]} // São Paulo
    zoom={15}
    style={{ width: '100%', height: ' 100%' }}
  >
    <TileLayer
      url={`https://api.mapbox.com/styles/v1/mapbox/light-v10/tiles/256/{z}/{x}/{y}@2x?access_token=${process.env.REACT_APP_MAPBOX_TOKEN}`}
     />
     /* url to use mapbox */
  </Map>
