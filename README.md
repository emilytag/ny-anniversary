# ny-anniversary
Mapping a year of living in NYC using D3

This is a small animated viz made in D3 to practice mapping and celebrate a year of living in New York. 

The viz reads from a json of coordinates downloaded from my personal Google Maps data.
For each location mapped in the data the viz animates to show the paths I traveled in my first year of living in the city.


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
