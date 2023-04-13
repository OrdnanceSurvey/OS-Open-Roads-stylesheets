# OS Open Roads

These are **QML** files for OS Open Roads in **Geopackage** format for use in **GeoServer**.

*They have been designed to work with the data loaded into a database, for example PostGIS, with field names in full and in lowercase.*

*They have been designed to work with the geopackage data downloaded from the OS DataHub **prior to April 2023***

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/archive/master.zip) the contents of this repository.

**2.**  Load your OS Open Roads data into GeoServer.

**3.**  Add the styles. If using the GUI then navigate to Styles > Add a new style > Browse and select to add each file in turn.

**4.**  Publish these styles with the data. If using the GUI then navigate to Layers > Add a new resource and choose them from the relevant database to add each file in turn, click on publish, configure settings and then choose the matching style before saving.

**5.**  We have given you two options for styling RoadLink. Use the RoadLink-1.sld file to style by road classification or select the RoadLink-2.sld file to style by a combination of route hierarchy and form of way.

**6.** To create OS Open Roads in GeoServer you will need to create a Layer Group. If using the GUI then navigate to Layer Groups > Add new layer group > Add Layer and choose each layer in turn to create the following layer order:

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/raw/master/GML%20stylesheets/GeoServer%20stylesheets%20(SLD)/images/OS_Open_Roads_layer_order.png "Recommended Layer Order")

The scale denominators have been set to allow viewing between **1:250** and **1:100 000**, although this will vary slightly by resolution with some layers limited to larger scales.

Your data should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Roads-stylesheets/raw/master/GML%20stylesheets/GeoServer%20stylesheets%20(SLD)/images/OS_Open_Roads_screenshot.png "Screenshot of OS Open Roads")

## Compatibility notes

Although SLD is an open OGC standard, these SLDs do contain some extended code used by GeoServer, namely the ‘vendor option’ tags. Also, as aforementioned, the field names referenced in the SLDs are in full and in lowercase.

## Additional information

[For more information about data styling and visualisation, take a look at our GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS Open Roads](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
