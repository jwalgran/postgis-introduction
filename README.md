# An Introduction to PostGIS #

A presentation prepared for the January 2013 Philadelphia PostgreSQL User Group meetup.

## Handout ##

[The handout for the presentation](https://github.com/jwalgran/postgis-introduction/blob/master/IntroductionToPostGIS.pdf?raw=true) is available on [GitHub](https://github.com/jwalgran/postgis-introduction)

## The PostGISLab Virtual Machine ##

You can [download a copy of the virtual machine](https://www.dropbox.com/s/79xpuzm59cmsj3a/PostGISLab.zip) (2.54GB zipped)

The virtual machine was created using [VirtualBox](https://www.virtualbox.org) and has the following open source software installed:

  - Ubuntu Desktop 12.04.1 32-bit
  - PostgreSQL 9.1.7
  - PROJ 4.8.0
  - GEOS 3.3.6
  - GDAL 1.9.2
  - PostGIS 2.0.2
  - pgAdmin III 1.14
  - qGIS 1.8

The VM will automatically log in as the user `postgis` with the password `postgis`.

## Data ##

All data files linked below are available in the `Data` directory in the `postgis` user's home folder along with scripts for loading and querying the data.

  - [Philadelphia Neighborhoods Shapefile](http://www.azavea.com/index.php/download_file/view/235/)
  - [Philadelphia Libraries Shapefile](http://www.pasda.psu.edu/uci/PhiladelphiaAgreement.asp?File=http://www.pasda.psu.edu/philacity/data/PhiladelphiaLibraries201201.zip)
  - [Philadelphia Police Part One Crime Incidents CSV](http://gis.phila.gov/data/police_inct.zip)
  - Azavea office coordinates
    - 2272 (PA State Plane): 2694727, 238558
    - 4326 (Lat/Lon): -75.1590100537934, 39.958950112686

## Links ##

  - [The event page for this meetup](http://www.phlpug.org/events/95352552/)
  - [The PostGIS home page](http://postgis.refractions.net)
  - [The PostGIS 2.0 manual](http://postgis.net/docs/manual-2.0/)
  - [OpenGeo Introduction to PostGIS Workshop](http://workshops.opengeo.org/postgis-intro/)
  - [OpenDataPhilly](http://www.opendataphilly.org)
  - PostGIS Dependancies
    - [PROJ.4 Cartographic Projections Library](http://trac.osgeo.org/proj/)
    - [GEOS - Geometry Engine, Open Source](http://trac.osgeo.org/geos/)
    - [GDAL - Geospatial Data Abstraction Library](http://www.gdal.org)
  - Prebuilt packages and installers
    - [OpenGeo Suite Community Edition (OS X, Windows, Linux)](http://opengeo.org/products/suite/community/)
    - [PostGIS for OS X](http://www.kyngchaos.com/software:postgres)
    - [PostGIS for Windows](http://postgis.refractions.net/download/windows/#postgis-installers)
  - Applications Powered By PostGIS
    - [Cicero](http://www.azavea.com/products/cicero/live-demo/)
    - [PhillyTreeMap](http://phillytreemap.org/map/)
    - [Visualizing Emancipation - University of Richmond](http://dsl.richmond.edu/emancipation/)
    - [My Clinical Trial Locator](http://myclinicaltriallocator.com)
  - [CartoDB - PostGIS as a service](http://cartodb.com) 

## Questions? ##

@jwalgran for shorties, justin@walgran.com for longies.

