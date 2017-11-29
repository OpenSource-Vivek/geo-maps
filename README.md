<h1 align="center">
  <a href="https://github.com/simonepri/geo-maps"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps.jpg" alt="geo-maps" /></a>
</h1>
<p align="center">
  <a href="https://github.com/tmcw/awesome-geojson"><img src="https://awesome.re/mentioned-badge.svg" alt="awesome-geojson" /></a>
  <a href="https://github.com/simonepri/geo-maps/releases"><img src="https://img.shields.io/github/tag/simonepri/geo-maps.svg" alt="total downloads" /></a>
  <a href="http://geojson.org/"><img src="https://img.shields.io/badge/format-GeoJSON-e67e22.svg" alt="maps format" /></a>
  <a href="http://www.openstreetmap.org/"><img src="https://img.shields.io/badge/source-OSM-2ecc71.svg" alt="maps source" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/simonepri/geo-maps.svg" alt="software license" /></a>
  <a href="https://opendatacommons.org/licenses/odbl/1.0/"><img src="https://img.shields.io/badge/license-ODbL-2980b9.svg" alt="data license" /></a>
</p>
<br />
<p align="center">
  🗺 High Quality GeoJSON maps programmatically generated.
</p>
<p align="center">
  <sub>
    The only GeoJSON maps of the world you will ever need!
  </sub>
</p>

## Motivation
The purpose of this project is to **programmatically** extract maps from open
databases like [OpenStreetMap](https://www.openstreetmap.org) providing you
with a ready to use GeoJSON map that fits your needs.  

Do you believe that this is cool? If so, <a href="#start-of-content">support us with a ⭐️</a>!

## Table of maps
In this section you can find all the maps generated by this project.  
Feel free to [propose](https://github.com/simonepri/geo-maps/issues) new kinds of maps! 🎉  

For each map you can click on the image to see a live preview.  
Please note that the previews show you the worst resolution available.  
See the details for higher resolutions.

All the maps are exported as GeoJSON and available to be downloaded directly from
[GitHub](https://github.com/simonepri/geo-maps/releases) or as package on [npm](https://www.npmjs.com/org/geo-maps).  
See the details of each map for more information on how to get started.

Preview | Name | Short Description | Info Page
--------|------|-------------------|----------
<a alt="see countries-land on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/countries-land.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-countries-land-hover.png" height ="100px"/></a> | **countries-land** | Countries' political land borders | <a alt="See countries-land details" href="info/countries-land.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see countries-coastline on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/countries-coastline.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-countries-coastline-hover.png" height ="100px"/></a> | **countries-coastline** | Countries' political coastline borders | <a alt="See countries-coastline details" href="info/countries-coastline.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see countries-maritime on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/countries-maritime.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-countries-maritime-hover.png" height ="100px"/></a> | **countries-maritime** | Countries' political maritime borders | <a alt="See countries-maritime details" href="info/countries-maritime.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-lands on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-lands.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-lands-hover.png" height ="100px"/></a> | **earth-lands** | Earth's lands | <a alt="See earth-lands details" href="info/earth-lands.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-coastlines on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-coastlines.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-coastlines-hover.png" height ="100px"/></a> | **earth-coastlines** | Earth's coastlines | <a alt="See earth-coastlines details" href="info/earth-coastlines.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-waterbodies on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-waterbodies.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-waterbodies-hover.png" height ="100px"/></a> | **earth-waterbodies** | Earth's waterbodies | <a alt="See earth-waterbodies details" href="info/earth-waterbodies.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-seas on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-seas.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-seas-hover.png" height ="100px"/></a> | **earth-seas** | Earth's seas and oceans | <a alt="See earth-seas details" href="info/earth-seas.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-lakes on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-lakes.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-lakes-hover.png" height ="100px"/></a> | **earth-lakes** | Earth's lakes | <a alt="See earth-lakes details" href="info/earth-lakes.md"><img src="media/details-button.png" height ="50px"/></a>
<a alt="see earth-rivers on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://cdn.rawgit.com/simonepri/geo-maps/next/previews/earth-rivers.geo.json"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/next/media/geo-maps-earth-rivers-hover.png" height ="100px"/></a> | **earth-rivers** | Earth's rivers | <a alt="See earth-rivers details" href="info/earth-rivers.md"><img src="media/details-button.png" height ="50px"/></a>

## Conversion to other formats
If you need to convert maps in any of Shapefile, TopoJSON, CSV, SVG formats you can use the [mapshaper's web interface](mapshaper.org) to export the map in the format of your need.  

## Showcase
Do you use geo-maps in your application? Please [open a Pull Request](https://github.com/simonepri/geo-maps/pulls) to include it here.  
We would love to have it in our list.

## Development
PRs are **REALLY** welcome.  
Scripts used to build maps are all contained in the [gulp](gulp/) folder.  

To release the project the following actions needs to be executed from the root.
```
$ npm i
$ npm run test
$ npm run build
$ npm run previews
$ npm run release
$ npm run publish
```

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/simonepri/geo-maps/tags).

## Authors
* **Simone Primarosa** - [simonepri](https://github.com/simonepri)

See also the list of [contributors](https://github.com/simonepri/geo-maps/contributors) who participated in this project.

## License
All data of this project is licensed under the [Open Data Commons Public Domain Dedication and License](https://opendatacommons.org/licenses/odbl/1.0/) as stated in [OpenStreetMap License](http://www.openstreetmap.org/copyright)

All source code of this project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
