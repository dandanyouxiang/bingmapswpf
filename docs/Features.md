# Features and RoadMap
## Release 1

The current version of InfoStrat.VE supports these features:

**VEMap and SurfaceVEMap:**
* Use WPF data binding to control various map properties:
	* Latitude and Longitude
	* Altitude
	* Roll, Pitch, and Yaw
	* Map Mode (Aerial, Hybrid, Road)
	* 3D Cursor (WPF only)
	* Show 3D Buildings
* Simple functions allow cinematic FlyTo a location
* Supports children objects such as pure WPF-based VEPushPin and SurfaceVEPushPin objects
	* Child objects automatically track a Latitude and Longitude on the map
	* Map can use VEPushPins through data binding, just like a ListBox or other ItemsControl
	* VEPushPins have optional max/min altitude and parent pushpin for grouping purposes
* You can inherit VEPushPin and SurfaceVEPushPin and create your own custom look and behavior

**SurfaceVEMap only:**
* Multi-touch/gesture manipulations for controlling Latitude and Longitude (pan) and Altitude (zoom)
* Data binding for Pan and Zoom gesture sensitivity (SurfaceVEMap only)

**Sample applications:**
* Demonstrates basic data binding
* Shows simple VEPushPin operations
## Release 2 (2H 2009)

The following features are currently in development and testing and are planned for the next version:

**VEMap and SurfaceVEMap:**
* Utility functions for processing geoRSS, WMS layers, and KML data

**SurfaceVEMap only:**
* Altitude aware gesture sensitivity
* Standardized gestures for controlling roll, pitch, and yaw

**Sample applications:**
* Sample showing geoRSS, WMS, and KML integration
* Sample showing VEPushPin grouping, altitude awareness, and better VEPushPin data source management