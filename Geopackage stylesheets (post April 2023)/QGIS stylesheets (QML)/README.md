# OS Open Roads

These are **QML** files for OS Open Roads data as supplied in **Geopackage** format for use in **QGIS**.

*These stylesheets are designed to be used with the geopackage data downloaded from the OS DataHub **after April 2023***

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/archive/master.zip) the contents of this repository

**2.**  Load your Open Roads geopackage data into QGIS

**3.**  Double click on a layer to access the 'Layer Properties' window > click on 'Load Style...' > navigate to the directory containing the QML files (those ending .qml) > select the relevantly named QML file > click 'Open' > click 'OK'

Repeat step 4 for all layers.

We recommend the following layer order and visibility:

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/blob/8e44693c7cea9015b43e9811651204be6a2c4b91/Geopackage%20stylesheets%20(post%20April%202023)/QGIS%20stylesheets%20(QML)/images/OS_Open_Roads_layer_order.JPG "OS Open Roads layer order")
  
The road_link1 style is a simple overview style with roads styled based on the 'class' attribute (e.g. A Road, B Road, Unclassified etc.). The road_link2 style uses more attributes to determine the road style. Roads are styled based on the road 'function', whether it is a 'primary' road and the 'formOfWay' (e.g. A Road, Primary, Dual Carriageway). The user can select which of these two road styles to use dependent on their use case.

We recommend viewing the Open Roads data between **1:250** and **1:100,000** for maximum legibility

Your data should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/blob/0a8e651d0d3d9fd069d94485f70e6898ac02345d/Geopackage%20stylesheets%20(post%20April%202023)/QGIS%20stylesheets%20(QML)/images/OS_Open_Roads_screenshot.JPG "Screenshot of OS Open Roads")

## Additional information

[For more information about data styling and visualisation, take a look at our GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS Open Roads](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
