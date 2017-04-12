# WMS-Server-List

The _WMSServerList.ini_ is a collection of public WMS services for _Maps Online App_ from Origin/OriginPro. This page provides the following information about each service:

* **Name** of the WMS service.
* **RUL** for REQUEST=GetCapabilities
* **GETMAP** for REQUEST=GetMap
* **Preview** shows a particular preview of one layer. If the image does display correctly, probably the service is down or forbidden.

You can download the _WMSServerList.ini_ or just copy the entry to your local file _MapsOnline.ini_.

---
```
[NASA Earth Observations (NEO) WMS]
URL=https://neo.sci.gsfc.nasa.gov/wms/wms
GETMAP=https://neo.sci.gsfc.nasa.gov/wms/wms
```
![BlueMarbleTB](https://neo.sci.gsfc.nasa.gov/wms/wms?REQUEST=GetMap&SERVICE=WMS&LAYERS=BlueMarbleNG-TB&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=-180.000000,-90,180,90&VERSION=1.3.0&CRS=CRS:84&WIDTH=512&HEIGHT=256&BGCOLOR=0xFFFFFF)
---
---
```
[WMS for Chlorophyll-a, Aqua MODIS, NPP, Global, Science Quality (8 Day Composite)]
URL=http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request?VERSION=1.1.1
GETMAP=http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request
```
![Land, Lakes and Rivers](http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request?REQUEST=GetMap&SERVICE=WMS&LAYERS=Land,LakesAndRivers&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=0,-90,360,90&VERSION=1.1.1&SRS=EPSG:4326&WIDTH=512&HEIGHT=256&BGCOLOR=0xFFFFFF)
---
