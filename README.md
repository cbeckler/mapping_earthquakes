# Mapping Earthquakes

## Overview of Project

### Purpose

The analyst created an interactive webpage for users to explore data related to recent earthquakes using Javascript and HTML. The webpage functions via interaction with JS GeoJSON objects. Users have access to a global map that tracks earthquakes from the last 7 days via API. Users can select from 3 map appearance options, and have 3 additional overlay options: all earthquakes, major earthquakes, and tectonic plates. Clicking on the marker for each earthquake will give users information about location and magnitude.

The code used for the backend functionality may be found [here](https://github.com/cbeckler/mapping_earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js).

### Deliverable

The fully interactive webpage looks like this when first loaded:

![default page view](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/page_default.png)

Two different view modes are also enabled, satellite view and dark mode:

![satellite page view](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/satellite_view.png)

![dark mode page view](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/dark_view.png)

In addition to the view modes, there are informational overlays that can be toggled on or off. They are all on by default. 

One overlay is major earthquakes, which will display only earthquakes classfied as major. It overlays the all earthquakes layer, and adds a red gradiant to track severity within major quakes. When all earthquakes is disabled, this layer can be used to view major earthquakes in isolation:

![major quakes only](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/major_on.png)

Additionally, this layer can be turned off to view all earthquakes without any additional major quake information:

![major quakes off](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/major_off.png)

There is also a layer showing tectonic plates. This layer can be seen in isolation with all earthquake layers turned off:

![tectonic plates map](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/all_eq_off.png)

Or the tectonic plates layer can be turned off to view only earthquakes:

![no tectonic plates map](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/tectonic_off.png)

Finally, whenever any earthquake layer is enabled, users can click on the marker to get addtional information about the earthquake:

![earthquake info](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/marker.png)

The map also has zoom capability, which can help when viewing smaller scale quakes:

![zoomed in map](https://github.com/cbeckler/mapping_earthquakes/blob/main/Resources/zoom.png)

## Summary 

The webpage the analyst has created allows users to interact with geographic data, guiding their explorations alone multiple layers of information. This allows users to direct their own experiences, with the ability to focus on specific regions or categories of information. Additionally, while the API is not live on this version of the webpage since it is a public repo, the analyst would be able to use similar API architecture to make live updating websites for any privately hosted projects. 

This type of project infrastructure would be ideal for any reporting for which geography and/or live updates are of significant importance. The scale for this webpage is global, but these maps can be focused down to neighborhood level or anywhere in between. The analyst recommends this type of reporting for public-facing data projects that are geographically significant.

