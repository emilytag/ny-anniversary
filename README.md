# ny-anniversary
Mapping a year of living in NYC using D3

This is a small animated viz made in D3 to practice mapping and celebrate a year of living in New York. 

The viz reads from a json of coordinates downloaded from my personal Google Maps data.
For each location mapped in the data the viz animates to show the paths I traveled in my first year of living in the city.
![screenshot of pathing](https://github.com/emilytag/ny-anniversary/blob/master/screenshots/pathing1.png)
a screenshot from early in the animation
![screenshot of pathing](https://github.com/emilytag/ny-anniversary/blob/master/screenshots/pathing3.png)
a screenshot nearing the end of a first year's worth of traveling

The map itself is responsive using Leaflet. You're able to zoom and scroll as the pathing animates without interrupting the path.

While I no longer live or work in any of these locations, I won't be providing the json of locations for privacy reasons.
The structure of the data looks like this if you'd like to replicate it on your own
```
"features": [
        {
            "geometry": {
                "type": "Point",
                "coordinates": [
                    0.0,
                    0.0
                ]
            },
            "type": "Feature",
            "properties": {
                "latitude": 0.0,
                "id": "2017-09-01",
                "longitude": 0.0,
                "time": 1
            }
        },
        ...
```
One you have the data you should be able to run a simple web server and watch the viz locally.
