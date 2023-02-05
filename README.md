# Mapty

## Keeps track of activities on a map

The application uses Geolocation and Leaflet APIs in order to get the location of the user and display the map. Clicking somewhere on the map, the user can register an activity that can be either Running or Cycling. The two activities have different parameters (distance, duration, cadence, elevation). When an activity is registed, the summary is saved in the activity container, and also displayed as a Waypoint on the map. Pressing on the activity will center the map on that waypoint.

## Architecture

The architecture of the application:
![architecture](/Mapty-architecture-final.png)

## Implementation details

The activities are stored in local storage. Deleting an activity will also delete the waypoint from the map.
For the map I used the Leaflet library, which provides an API to show the map. I followed the documentation in order to understand how it works and what I have to change in order to match my needs.

## Skills acquired

- Project planning - how to organize the project starting with user stories, flow chart and finally, the architecture
- Learned OOP by working with classes and inheritance. Also created prototypes
- Defer/Async script loading
- Guard clause
