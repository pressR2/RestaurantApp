## Restaurant Reviews App - Stage 1
Main goal of the project is to level up students skills in responsive design, service worker and accessibility areas, while practicing on a static webpage and transforming it to a mobile-ready web application.
### How to use?
This website allows the user to search for a restaurant. On the main page search can be filtered by location and cuisine type.
By clicking on the **View Details** link users can see more information on the restaurant i.e. the address, opening hours and reviews with rating.
### How to deploy?
##### Requirements
* This project needs a web server to run. For Chrome users here's example [Web Server for Chrome extension](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en).
* You will need to create [MapBox](https://www.mapbox.com/) account to get your own API key.

To get started clone the [repository](https://github.com/udacity/mws-restaurant-stage-1.git). Set up your webserver port and domain in `dbhelper.js`.
##### Example

```
static get DATABASE_URL() {
    const port = 8887 // Change this to your server port
    return `http://localhost:${port}/data/restaurants.json`;
  }
```
Replace `<your MAPBOX API KEY HERE>` inside of `main.js` with your key.
### Dependencies
[leaflet](https://leafletjs.com/)
[MapBox](https://www.mapbox.com/)


