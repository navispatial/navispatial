## Code by Navibyte

- 👋 Hi, I’m @navispatial, coding solutions [@navibyte](https://github.com/navibyte)
- 👀 I’m interested in [Dart](https://dart.dev/) 🎯 and [Flutter](https://flutter.dev/) 💙 development
- 🔭 Exploring also geospatial solutions 🌍 and API design ✍️
- 🌱 I’m currently learning to be Full-Stack Dart developer
- 📡 You can also follow tweets by [@navibyte](https://twitter.com/navibyte) (DMs open) 
- 🏡 I'm located in Finland 🇫🇮

## Geospatial tools for Dart

✨ New (2023-10): See also the article [Geospatial tools for Dart - version 1.0 published](https://medium.com/@navibyte/geospatial-tools-for-dart-version-1-0-published-0f9673e510b3) at Medium.

🧭 The [geospatial](https://github.com/navibyte/geospatial) code repository with
geospatial data structures, tools and utilities for [Dart](https://dart.dev/)
and [Flutter](https://flutter.dev/) - coordinates,
geometries, feature objects, metadata, spherical geodesy, projections, tiling
schemes, vector data models and formats, and geospatial Web APIs.

📦 The code package published at
[pub.dev](https://pub.dev/publishers/navibyte.com/packages):

Code           | Package | Description 
-------------- | --------| -----------
:globe_with_meridians: [geobase](https://github.com/navibyte/geospatial/tree/main/dart/geobase) | [![pub package](https://img.shields.io/pub/v/geobase.svg)](https://pub.dev/packages/geobase) | Geospatial data structures (coordinates, geometries, features, metadata), spherical geodesy, projections and tiling schemes. Vector data format support for [GeoJSON](https://geojson.org/), [WKT](https://en.wikipedia.org/wiki/Well-known_text_representation_of_geometry) and [WKB](https://en.wikipedia.org/wiki/Well-known_text_representation_of_geometry#Well-known_binary).
:earth_americas: [geodata](https://github.com/navibyte/geospatial/tree/main/dart/geodata) | [![pub package](https://img.shields.io/pub/v/geodata.svg)](https://pub.dev/packages/geodata) | Geospatial feature service Web APIs with support for [GeoJSON](https://geojson.org/) and [OGC API Features](https://ogcapi.ogc.org/features/) clients.

🧩 See [open issues](https://github.com/navibyte/geospatial/issues) for planned features, requests for change, and observed bugs. 

## Geospatial demos for Dart

✨ See also the
[Geospatial demos for Dart](https://github.com/navibyte/geospatial_demos) code
repository for demo and sample apps demonstrating the usage of
[geobase](https://pub.dev/packages/geobase) and
[geodata](https://pub.dev/packages/geodata) along with other topics.

Code          | Description 
------------- | -----------
[earthquake_map](https://github.com/navibyte/geospatial_demos/tree/main/earthquake_map) | Shows earthquakes fetched from the [USGS web service](https://earthquake.usgs.gov/earthquakes/feed/) on a basic map view. The demo uses both [geobase](https://pub.dev/packages/geobase) and [geodata](https://pub.dev/packages/geodata) packages for geospatial data accesss. Discusses also state management based on [Riverpod](https://riverpod.dev/). The map UI is based on the [Google Maps Flutter](https://pub.dev/packages/google_maps_flutter) plugin.

📅 The first version of this repository was published in August 2022, updated
October 2023.

## Older samples and demos

Some code samples (*Last updated: Feb 2020*) also, code at GitHub:

Code          | Demo | Description 
------------- | ---- | -----------
[quake](https://github.com/navibyte/quake) | - | A gRPC service for monitoring earthquakes based on data provided by the USGS.
[quake_monitor](https://github.com/navibyte/quake_monitor) | [demo](http://bit.ly/quake-monitor) | Flutter app, deployed to web, to monitor earthquakes with two backend service integrations choices (RESTful API and a gRPC service).
