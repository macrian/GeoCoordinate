# GeoCoordinate

![.NET Core Build and Run Unit Tests](https://github.com/DevsAnon/GeoCoordinate/workflows/.NET%20Core%20Build%20and%20Run%20Unit%20Tests/badge.svg)

A re-implementation of GeoCoordinate class for .Net standard.</br>
This class is not an exact clone of System.Device.Location but an extension of the functionality of the original.</br>
You can install package by calling `Install-Package ExtendedGeoCoordinate`

Differences between this class and the Microsoft default class are

<ol>
  <li> Object is immutable. Once created, it can not be edited.</li>
  <li> Distance calculation can be done in three possible ways (using three different formulas)
    <ul><li>Haversine Formula</li>
    <li>Spherical law of Cosines</li>
    <li>Vicenty's formula</li></ul></li>
  <li>ToString method has overload for printing in DMS format</li>
  <li>GetBearing method to calculate azimuth between two points</li>
  <li>Deconstructors exist to break down the object to Lat/Lon and Lat/Lon/Alt</li>
  <li>Added support for altitude Units</li>
  </ol>


Project will be supported, maintained and upgraded until Microsoft ports GeoCoordinate class to .Net Standard. 

Link to nuget Gallery [here](https://www.nuget.org/packages/ExtendedGeoCoordinate/)

## Contributing
Contributions are always welcome! Please feel free to submit pull requests and to open issues. I prefer to have tests on all public methods if possible and where ever else makes sense.
