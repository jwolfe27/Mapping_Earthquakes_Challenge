<h1 align="center">Mapping Earthquakes Challenge</h1>


<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/142674629-ed437f72-d8e4-4cbe-8d39-73983acaa9d9.gif">
</p>

## Purpose of the Project
The purpose of this project was to build an interactive map showing all recorded earthquake events and their respective magnitudes for the past 7 days around the globe.  The map also shows the tectonic fault line locations. The map provides the user the ability to change what data is being viewed, as well as which view mode they prefer as shown below: 

<h2 align="center"> Streets View Mode</h2>

![Streets view](https://user-images.githubusercontent.com/89044350/142680186-0e209740-cb44-43d3-ad96-98e60deb857c.JPG)

<h2 align="center"> Satellite View Mode</h2>

![Satellite View](https://user-images.githubusercontent.com/89044350/142680312-a8642f45-3d7e-4f1a-9c12-bed03cd29f56.JPG)

<h2 align="center"> Dark View Mode</h2>

![Dark View](https://user-images.githubusercontent.com/89044350/142680371-c03c1a3a-20f8-4b79-ba26-84e0ef60f4c0.JPG)

## Workload
To complete this project we used GeoJSON data from the USGS website to retrieve the geographical coordinates for earthquake events, and each events respective magnitude over the past 7 day period.  The data was then added to an interactive map containing multiple layers and data filters.

## Map Explaination
The size and color of the dots represents the magnitude of the earthquake event.  The lighter the color and smaller the size, the lower the event was in terms of magnitude.  The larger, more red dots displays a larger earthquake event in respect to magnitude.  A legend was created as a reference:

![Legend](https://user-images.githubusercontent.com/89044350/142681496-b11a8c1c-9d34-48c8-b726-687c1d9dc225.JPG)

The below image is the filter selection provide to the user:

![Data Layers](https://user-images.githubusercontent.com/89044350/142682101-3c6e928f-95a0-4a0f-8274-26f0cb4e56b6.JPG)

## Summary
The user is provided a user friendly, interactive map to view all of the earthquake events around the globe over the past 7 days.  Viewing the map, it is easy to determine that the majority of all earthquake events happen along tectonic fault lines.  There are a few earthquake events a good distance away from fault lines, but did not register very high on the magnitude scale.
