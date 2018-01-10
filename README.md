# Geocoding API

A simple web appl using Google Maps Geocoding API that allows users to enter location data and get the address, city, county, state, country, longitude and latitude returned. Axios was used to handle API calls and Bootstrap 4 was used for basic styling/formatting.

To run this app, you'll need a Google API key. Once you have one, go to `javascripts/main.js` and go to the axios get method. There is an empty string labled "key". Paste your key there and you're good to go. See code block below.

```
    axios.get('https://maps.googleapis.com/maps/api/geocode/json?',{
        params:{
            address: location,
            key: '',//API KEY GOES HERE
        }
    })
```

I used <a href="https://www.youtube.com/watch?v=pRiQeo17u6c">this video</a> as a guide for this project.