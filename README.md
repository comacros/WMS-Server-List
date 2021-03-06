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
[WMS for Chlorophyll-a, Aqua MODIS, NPP, Global, Science Quality (8 Day Composite)]
URL=http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request?VERSION=1.1.1
GETMAP=http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request
```
![Land, Lakes and Rivers](http://oos.soest.hawaii.edu/erddap/wms/erdMHchla8day/request?REQUEST=GetMap&SERVICE=WMS&LAYERS=Land,LakesAndRivers&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=0,-90,360,90&VERSION=1.1.1&SRS=EPSG:4326&WIDTH=512&HEIGHT=256&BGCOLOR=0xFFFFFF)

---
```
[WMS for the GEBCO global bathymetric grid]
URL=http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv?VERSION=1.1.1
GETMAP=http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv
```
![GEBCO_Grid](http://www.gebco.net/data_and_products/gebco_web_services/web_map_service/mapserv?REQUEST=GetMap&SERVICE=WMS&LAYERS=GEBCO_Grid&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=-180,-90,180,90&VERSION=1.1.1&SRS=EPSG:4326&WIDTH=512&HEIGHT=256&BGCOLOR=0xFFFFFF)

_* Imagery reproduced from the GEBCO_2014 Grid, version 20150318, www.gebco.net_ 

---
```
[Europakart WMS]
URL=http://wms.geonorge.no/skwms1/wms.europa?SERVICE=WMS&VERSION=1.1.1
```
![Europa_WMS](http://wms.geonorge.no/skwms1/wms.europa?REQUEST=GetMap&SERVICE=WMS&LAYERS=Europa_WMS&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=-15,28,47,82&VERSION=1.1.1&SRS=EPSG:4326&WIDTH=434&HEIGHT=378&BGCOLOR=0xFFFFFF)

---
```
[Ortofotos PNOA máxima actualidad]
URL=http://www.idee.es/wms/PNOA/PNOA
```
![PNOA](http://www.idee.es/wms/PNOA/PNOA?service=wms&request=getmap&bbox=-19,27,5,44&layers=pnoa&width=434&height=307&version=1.3.0&crs=crs:84&format=image/png&bgcolor=0xf0f8ff)

---
```
[OneGeology China]
URL=http://onegeologychina.cgs.gov.cn/cgi-bin/mapserv.exe?map=C:/ms4w/apps/CHINAGEOLOGY/CHINA1MMAP_ENGLISH41GG.map&
```
![OneGeology China](http://onegeologychina.cgs.gov.cn/cgi-bin/mapserv.exe?map=C:/ms4w/apps/CHINAGEOLOGY/CHINA1MMAP_ENGLISH41GG.map&REQUEST=GetMap&SERVICE=WMS&LAYERS=CGS_EN_Bedrock_Geology&FORMAT=image/png&TRANSPARENT=FALSE&EXCEPTIONS=XML&STYLES=&BBOX=18.1605,73.498100,28.1605,93.4981&VERSION=1.3.0&CRS=EPSG:4326&WIDTH=256&HEIGHT=128&BGCOLOR=0xFFFFFF)

----

