# sprutregn.no

## TODO:
- [ ] Connect to an API where you can get `lon` and `lat` from searching for a place in the world
  - [x] Gotten a initial response
- [ ] Connect to yr's weather api (it uses `longitude` and `latitude` )
  - [x] Inital weather is fetched via Postman

- [ ] Create a service worker to prevent unnecessary requests
- [ ] "Translate" the amount of rain to sprutregn or SPRUTREGN etc. 
- [ ] Visually display the data
- [ ] Use the Open Street Map to make something cool 



## Explanation: 

1. MapBox to get lon/lat from searching for a place. 

    eg: 

    ```
    GET: https://api.mapbox.com/geocoding/v5/mapbox.places/Stockholm.json?access_token=token
    ```

2. Use met-api to get the forecast by using log/lat gotten from Mapbox

  
    https://api.met.no/


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
