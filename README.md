# isybau2qgep

Instructions on using the (german specific) wastewater data format ["ISYBAU Austauschformate Abwasser (XML)"](http://www.arbeitshilfen-abwasser.de/html/A7ISYBAU_ATF_XML.html) in [QGIS](https://qgis.org) and the QGIS based waste-water application [QGEP](https://github.com/QGEP/QGEP).

Anleitung für die Verwendung der [ISYBAU Austauschformate Abwasser (XML)](http://www.arbeitshilfen-abwasser.de/html/A7ISYBAU_ATF_XML.html) in [QGIS](https://qgis.org) sowie in Verbindung mit der QGIS-basierten Abwasserfachschale [QGEP](https://github.com/QGEP/QGEP).

## Ziel A: Einfache Anzeige und Nutzung von ISYBAU XML in QGIS
* Verwendung des **[OGR Treibers GMLAS]**(http://www.gdal.org/drv_gmlas.html) (GDAL >= 2.2) 
* bzw. der [GML Application Schema toolbox](http://planet.qgis.org/plugins/gml_application_schema_toolbox/)
    * Schema
    * einlesen ogrinfo
    * importieren ogr2ogr

## Ziel B: Migration ins QGEP Schema
