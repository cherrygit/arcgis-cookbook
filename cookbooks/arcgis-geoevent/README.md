arcgis-geoevent cookbook
===============

This cookbook installs and configures ArcGIS GeoEvent Extension for Server.

Requirements
------------

### Supported ArcGIS software

* ArcGIS GeoEvent Extension for Server

### Supported ArcGIS software versions
* ArcGIS 10.4
* ArcGIS 10.4.1
* ArcGIS 10.5 Beta

### Platforms

* Windows 7
* Windows 8 (8.1)
* Windows 10
* Windows Server 2008 (R2)
* Windows Server 2012 (R2)
* Ubuntu 14.04 (when deploying ArcGIS Enterprise on Amazon Web Services)
* Rhel 6.5, 7.0

### Dependencies
The following cookbooks are required:

* arcgis-server

Attributes
----------

* `node['arcgis']['geoevent']['authorization_file']` = ArcGIS GeoEvent Extension for Server authorization file path. Default value is ``.
* `node['arcgis']['geoevent']['authorization_file_version']` = ArcGIS GeoEvent Extension for Server authorization file version. Default value is `node['arcgis']['server']['authorization_file_version']`.
* `node['arcgis']['geoevent']['setup']` = The location of ArcGIS GeoEvent Extension for Server setup executable. Default location is `C:\ArcGIS\GeoEvent\setup.exe` on Windows and `/arcgis/geo-event-cd/Setup.sh` on Linux.


Recipes
-------

### arcgis-geoevent::default
Installs and configures ArcGIS GeoEvent Extension for Server.

### arcgis-geoevent::lp-install
Installs language pack for ArcGIS GeoEvent Extension for Server.

### arcgis-geoevent::uninstall
Uninstalls ArcGIS GeoEvent Extension for Server.


Usage
-----

See [wiki](https://github.com/Esri/arcgis-cookbook/wiki) pages for more information about using ArcGIS cookbooks.

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an [issue](https://github.com/Esri/arcgis-cookbook/issues).

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

Licensing
---------

Copyright 2016 Esri

Licensed under the Apache License, Version 2.0 (the "License");
You may not use this file except in compliance with the License.
You may obtain a copy of the License at
   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [License.txt](https://github.com/Esri/arcgis-cookbook/blob/master/License.txt?raw=true) file.

[](Esri Tags: ArcGIS Chef Cookbook GeoEvent)
[](Esri Language: Ruby)