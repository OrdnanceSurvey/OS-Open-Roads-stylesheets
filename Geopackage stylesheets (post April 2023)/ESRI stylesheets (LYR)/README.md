# OS Open Roads

These are **LYR** files for OS Open Roads in **ESRI Shapefile** format for use in **ESRI ArcGIS**.

*They have been designed to work with the data as it is supplied. They have been designed to work the geopackage data downloaded from the OS datahub **after April 2023***

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/archive/master.zip) the contents of this repository

**2.**  Open a new blank map in ArcMap

**3.**  Click on the ‘Add Data’ button and navigate to the stylesheets folder and the directory that matches your data format, stylesheet format and style preference

**4.**  Select the layer file and click ‘Add’

**5.**  Your Table of Contents should now look like this. This is the recommended layer order: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/blob/12e1c1a670a67e3339a747923b7a41c331d56ab5/Geopackage%20stylesheets%20(post%20April%202023)/ESRI%20stylesheets%20(LYR)/images/OS_Open_Roads_layer_order.png "Recommended layer order for OS Open Roads")
  
The roadlink-1 style is a simple overview style with roads styled based on the 'class' attribute (e.g. A Road, B Road, Unclassified etc.). The roadlink-2 style uses more attributes to determine the road style. Roads are styled based on the road 'function', whether it is a 'primary' road and the 'formOfWay' (e.g. A Road, Primary, Dual Carriageway). The user can select which of these two road styles to use dependent on their use case.

We recommend viewing the map between **1:250** and **1:100,000** for maximum legibility

Your map should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/blob/b173038adf157700edc663bb3ba76e807017d7d2/Geopackage%20stylesheets%20(post%20April%202023)/ESRI%20stylesheets%20(LYR)/images/OS_Open_Roads_screenshot.png "Screenshot of OS Open Roads")

## Compatibility notes

Our Layer Files are compatible with versions of ESRI ArcGIS back to version 9.3 (released in 2008)

## Additional information

Spatial indexing of the data in ArcGIS will significantly improve performance (draw speed)

‘Hidden’ features can be activated through the relevant checkbox or by unchecking ‘Color is Null’ in the Color Selector dialogue

For more information about data styling and visualisation, take a look at our [GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS VectorMap District](http://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)


## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/)
