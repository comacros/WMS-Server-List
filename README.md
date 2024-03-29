# WMS-Server-List

The _WMSServerList.ini_ is a collection of public WMS services for _Maps Online App_ from Origin/OriginPro. This page provides the following information about each service:

* **Name** of the WMS service.
* **URL** for REQUEST=GetCapabilities
* **GETMAP** (optional) for REQUEST=GetMap
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
```
[WMS for the GEBCO global bathymetric grid]
URL=http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv?VERSION=1.1.1
GETMAP=http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv
```
![GEBCO_Grid](http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv?REQUEST=GetMap&SERVICE=WMS&LAYERS=GEBCO_Grid&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=-180,-90,180,90&VERSION=1.1.1&SRS=EPSG:4326&WIDTH=512&HEIGHT=256&BGCOLOR=0xFFFFFF)

_* Imagery reproduced from the GEBCO_2014 Grid, version 20150318, www.gebco.net_ 

---


