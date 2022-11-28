# OS Open Roads

These are **LYR** files for OS Open Roads in **Geopackage** format for use in **ESRI ArcGIS**.

*They have been designed to work with the data as it is supplied.*

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/archive/master.zip) the contents of this repository

**2.**  Open a new blank map in ArcMap

**3.**  Right-click on ‘Layers’ at the top of the Table Of Contents, select Properties… > then General > set Reference Scale to 1:25 000 and set the Label Engine to ‘Maplex Label Engine’

**4.**  In the same window select the Frame tab and change the Background colour to R 250 G 249 B 247, and under the Coordinate System tab > choose British National Grid. You may need to reposition to the data extent

**5.**  Click on the ‘Add Data’ button and navigate to the stylesheets folder and the directory that matches your data format, stylesheet format and style preference

**6.**  Select the layer file and click ‘Add’

**7.**  Your Table of Contents should now look like this. This is the recommended layer order: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/raw/master/ESRI%20Shapefile%20stylesheets/ESRI%20stylesheets%20(LYR)/images/OS_Open_Roads_layer_order.png "Recommended layer order for OS Open Roads")

**8.**  Double-click on a layer to access the ‘Layer Properties’ window > select the ‘Source tab’ > click on ‘Set Data Source…’ > navigate to your OS VectorMap District data > select the data that matches the layer, for example for MotorwayJunction select XX_MotorwayJunction.shp (XX being the 100km tile name) > select ‘Add’

Repeat step 8 for all layers.

We recommend viewing the map between **1:250** and **1:100,000** for maximum legibility

Your map should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/raw/master/ESRI%20Shapefile%20stylesheets/ESRI%20stylesheets%20(LYR)/images/OS_Open_Roads_screenshot.png "Screenshot of OS Open Roads")

## Compatibility notes

Our Layer Files are compatible with versions of ESRI ArcGIS back to version 9.3 (released in 2008)

## Additional information

Spatial indexing of the data in ArcGIS will significantly improve performance (draw speed)

‘Hidden’ features can be activated through the relevant checkbox or by unchecking ‘Color is Null’ in the Color Selector dialogue

[For more information about data styling and visualisation, take a look at our GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS VectorMap District](http://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/)
