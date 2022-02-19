import React from 'react'
import { GoogleMap, LoadScript } from '@react-google-maps/api';

const containerStyle = {
width: '400px',
height: '400px'
};

const center = {
lat: 37.3862, lng: 127.1224
};

function App() {
return (
<LoadScript
      googleMapsApiKey="AIzaSyCSYjuiuUYQ2tYtEE5V26yBzQhc5M6xjPM"
    >
<GoogleMap
        mapContainerStyle={containerStyle}
        center={center}
        zoom={10}
      >
{ /_ Child components, such as markers, info windows, etc. _/ }
<></>
</GoogleMap>
</LoadScript>
)
}

export default React.memo(MyComponent)
