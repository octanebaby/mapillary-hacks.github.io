# MYTrafficHack2017 - Using Mapillary in your Hacks

The MYTrafficHack2017 event will focus on solving such problems as traffic congestions monitoring, identifying roadway infrastructure needs, and emergency traffic management using the World Bank's Open Traffic dataset. Much of the data involved will include GPS coordinates and time stamps, as well as estimates of speed, but sometimes this isn't enough to paint the whole picture. In other cases, OpenStreetMap is used to give context to the city that the traffic exists within, but OSM can also be lacking in accuracy and completion. This is where Mapillary can help.

## Mapillary hack ideas

We are always thinking about how to use Mapillary in creative ways, and we present to you some of our hack ideas that you can freely commandeer to make this event a success for you. 

To get started, check out Mapillary coverage in and around Kuala Lumpur: https://www.mapillary.com/app/?lat=3.1771211542482547&lng=101.72597628336473&z=10&focus=map

It's extremely limited to just a few major roads. 

However, if you take some time to go out and **capture imagery** (guide here: https://github.com/mapillary/UserGuide/wiki/Capturing), you can generate more Mapillary material to drive your own ideas, or some ideas we've generated for you.

These ideas include:

* **Show photos inside both lowest and highest congestion areas to illustrate visual difference in road shape and size, infrastructure, and other physical attributes--are areas that photos show to contain houses always less congested than areas with apartments? Do 5 lane vs. 4 lane roads make a difference? Do you see sidewalks in congested areas?**
* **Match high volume traffic against detected street signs in Mapilly, to see if traffic congestion is associated with stop signs, crosswalks, change in speed limits, school zones, or other situations indicated by signs**
* **Estimate the number of traffic lanes in Mapillary photos, so you can tell exactly how narrow the roads may be**
* **Inspect roads for infrastructure problems by matching Mapillary photo locations to traffic hotspots**
* **Enable users in reporting of high traffic congestion, infrastructure problems, or traffic incidents by linking your app to Mapillary and enabling users to upload photos on the spot that are automatically reconstructed to allow for street level navigation in our viewer**

## Mapillary as a Tool

Mapillary is a collaborative street-level imagery platform powered by computer vision. Making images and data available to improve cities, build the maps of the future, and create safer transportation. 

Mapillary provides a variety of ways for you to harness its power in your hacks:

* **Capture your own imagery to give visual context to areas of interest:**
  * Download the Mapillary app on iOS and Android
  * Unofficial app for Windows phones
  * Use the mobile app to start capturing street level photos today, with your phone camera
  * Use your GoPro, 360 camera, or other action camera to capture photos and upload on our website
* **Use Mapillary to get a visual representation of the world, using Mapillary photos to:**
  * View areas on the map using images filtered by date
  * View locations of traffic signs and other traffic control objects
  * Verify accuracy of traffic GPS points by matching them to photos
  * Get a look at city infrastructure such as bridges and buildings
  * Find intersections, crosswalks, and highway on/off ramps
  * Verify OSM accuracy with photographic evidence
  * Compare photos of the same location at different times using Mapillary Time Travel
* **Use the Mapillary API to do deeper analysis:**
  * Search for images or sequences of images within a radius or bounding box
  * Filter photos by date and time, user, camera and compass angle
  * Estimate travel times between objects in photos by querying the time stamp of start and end photos
* **Use Mapillary vector tiles to:**
  * See the locations of Mapillary photo coverage
  * identify major routes which are more likely to have Mapillary photos
  * Give context to the location of photos seen in the viewer or queried in the API
  * See the GPS coordinates (latitude and longitude) of objects detected in photos, such as traffic signs
* **Use Mapillary for OSM iD Plugin:**
  * Use photos as a reference to add new objects to the map
  * Use photos to get a look at existing map objects, or confirm their existence

## Mapillary resources

You can get started with the above capabilities using the following links:

* Capture guide: https://github.com/mapillary/UserGuide/wiki/Capturing
* Open Source Photo viewer and navigator (MapillaryJS): https://mapillary.github.io/mapillary-js/
* Using standard vector tiles: https://www.mapillary.com/developer/tiles-documentation/#coverage
* Using map object tiles: https://www.mapillary.com/developer/tiles-documentation/#map-objects
* API Guide: https://www.mapillary.com/developer/api-documentation/
* OSM iD + Mapillary guide: https://github.com/mapillary/UserGuide/wiki/OSM

## Mapillary examples

You can also borrow freely from any of these sample and example projects, many of which have code in this repo:

* MapillaryJS examples: https://github.com/mapillary/mapillary-js#examples
* Add vector tiles to a Mapbox map: https://www.mapillary.com/developer/tiles-documentation/#mapbox-gl-js
* Measuring growth of Mapillary coverage over time: 
* Comparing photos over time: http://blog.mapillary.com/update/2016/10/21/time-travel.html
* Compare different maps in the same location: https://mapillary-hacks.github.io/hackathon/malaysia/compare/
* Compare Mapillary vector tiles with earthquake incident feeds: https://mapillary-hacks.github.io/hackathon/malaysia/earthquake/jp/
* Show Mapillary images in the context of city green infrastructure: https://cbeddow.github.io/bsas/
* See the `basic_maps` folder in this repo for examples of adding vector tiles and filtering them: 
