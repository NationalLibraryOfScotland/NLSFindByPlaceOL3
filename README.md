NLSFindByPlaceOL3
=================

This <a href="https://geo.nls.uk/maps/dev/NLSFindByPlaceOL3/index.html">demonstration application</a> uses <a href="https://openlayers.org/">OpenLayers v 3.6</a>, and <a href="https://geoserver.org/">GeoServer</a> to form a geographical retrieval inteface for historical maps. Searching is possible by zooming in on the map, with an option to change the map base layer between Bing, Ordnance Survey and OpenStreetMap layers. Searching is also possible by using a Nominatim gazetteer, a British National Grid Reference, as well as historic county and parish drop-down lists. 

The boundaries of historic maps are held as shapefiles within GeoServer, pre-rendered using GeoWebCache and customised for display using GeoServer Styled Layer Descriptors. Clicking on the map initiates a click handler which performs a Web Feature Service request to GeoServer, returning features that intersect with the point clicked upon. Selected fields from these features are returned to a right-hand 'Results' div/panel, and the features are highlighted on the map by creating a temporary vector layer overlay.

<a href="https://geo.nls.uk/maps/dev/NLSFindByPlaceOL3/index.html">This application</a> was originally developed by <a href="http://www.klokantech.com/">Klokan Technologies GmbH</a> for the <a href="https://www.nls.uk">National Library of Scotland<a> in 2011. Following discussion in 2014, the application is now released as open-source, ON CONDITION THAT IT IS DEVELOPED WITH A DIFFERENT IMPLEMENTATION OF GEOSERVER, AND NOT AS A REPLACEMENT OR ALTERNATIVE TO VIEWING THE NATIONAL LIBRARY OF SCOTLAND'S MAPS. We hope that other libraries, archives and institutions may benefit from the code in making available their geographical collections.

The application accompanies the <a href="https://github.com/NationalLibraryOfScotland/NLSExploreGeoreferencedMapsOL3">NLSExploreGeoreferencedMaps</a> Github repository and application, sharing a similar interface, use of OpenLayers, gazetteer search and css.

View a more <a href="https://maps.nls.uk/geo/find/">complete working version of the application</a> on the National Library of Scotland Map Images website.

