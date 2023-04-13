# OS Open Roads

These are **LYRX** files for OS Open Roads in **Geopackage** format for use in **ESRI ArcPro**.

*They have been designed to work with the data as it is supplied.*

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/archive/master.zip) the contents of this repository

**2.**  Open a new blank map in ArcPro

**3.**  Right-click on ‘Map’ at the top of the Contents panel, select Properties… > then General > set Reference Scale to 1:25 000 and set the Label Engine to ‘Maplex Label Engine’

**4.**  In the same window change the Background colour to R 250 G 249 B 247, and under the Coordinate System tab > choose British National Grid. You may need to reposition to the data extent

**5.**  Click on the ‘Add Data’ button and navigate to the stylesheets folder and the directory that matches your data format and stylesheet format

**6.**  Select the lyrx file and click ‘Add’

**7.**  Your Table of Contents should now look like this. This is the recommended layer order: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/blob/eac46696e7230864c2deb1d4a828860a336eb040/Geopackage%20stylesheets%20(post%20April%202023)/ESRI%20ArcPro%20stylesheets%20(LYRX)/images/OS_Open_Roads_layer_order.JPG "Recommended layer order for OS Open Roads")

**8.**  Double-click on a layer to access the ‘Layer Properties’ window > select the ‘Source' tab > click on ‘Set Data Source…’ > navigate to your OS Open Roads data > select the data that matches the layer > select ‘Add’

Repeat step 8 for all layers.

We recommend viewing the map between **1:250** and **1:100,000** for maximum legibility

Your map should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/raw/master/ESRI%20Shapefile%20stylesheets/ESRI%20ArcPro%20stylesheets%20(LYRX)/images/OS_Open_Roads_screenshot.JPG"Screenshot of OS Open Roads")


## Additional information

Spatial indexing of the data in ArcPro will significantly improve performance (draw speed)

‘Hidden’ features can be activated through the relevant checkbox or by unchecking ‘Color is Null’ in the Color Selector dialogue

[For more information about data styling and visualisation, take a look at our GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS Open Roads](http://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/)
