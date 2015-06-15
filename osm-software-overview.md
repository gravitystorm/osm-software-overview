
THIS IS A VERY ROUGH FIRST SKETCH TO GET THINGS GOING!

# OSM Software

Overview of the essential pieces that make up the OSM software eco-system.

This should document the pieces of software specific to the OSM world. It also
contains some major other software projects that need to be configured
specially or are important for some other reason.

XXX Integrate info from http://wiki.openstreetmap.org/wiki/Develop

XXX Info about Hosting, documentation, status, major issues, showstoppers, ...

XXX Add Info about File Formats (XML, PBF, ...)?

XXX Add Info about Services?
    - Tiles
    - Routing...
    - planet.osm.org
        dumps, diffs
    - Stats
    - Websites
        stateofthemap
        switch2osm
        osm foundation

XXX Add Info about APIs
    - Main API
    - Overpass
    - Nominatim
    - XAPI

## Essential Core Components (OSMF Servers)

### Rails Port

Maintainer: TomH
Depends on: Ruby on Rails
Languages: Ruby
Code hosting:
Documentation URL:
Status:

### Components for GPX upload/dump?

### cgimap

Maintainer: Matt
Languages: C++
Depends on: Rails Port

### Osmosis

maintainer: Brett Henderson

### OSM-Binary

Maintainer: Scott, Jochen (sort of)
Languages: C, C++, Java
Status: stable, no major work is done, Jochen maintains C++ side, several people
    have reported problems with the Java build

### planet-dump-ng

Maintainer: Matt

### Backup

### Server Hardware/OS, Chef

Sysadmin Team

## Non-Essential Core Components (OSMF Servers)

### Rendering stack

Depends on: osm2pgsql, renderd, mod_tile, dirty tile update, tile caching

### Nominatim

Maintainer: Sarah

Depends on: osm2pgsql

### Mediawiki

Extensions? (Harry Wood?, Firefishy)

### dirty tile update

Maintainer: Matt

### Tile Caching servers

Maintainer: Sysadmin team

### renderd

Maintainer: ?

### mod_tile

Maintainer: ?

### osm2pgsql

For rendering and Nominatim

Maintainer: Paul Norman, Sarah
Depends on: OSM-Binary

### iD

### taginfo

Maintainer: Jochen

Depends on: Libosmium


### routing engines

Maintainer: several

    yournavigation
    osrm


### Mailing list software

Maintainer: sysadmin team

### help.osm.org

Maintainer: sysadmin team

### CartoCSS Styles for main map

repos: openstreetmap-carto

## Other

### Libosmium

### OSMCoastline

Maintainer: Jochen

Depends on: Libosmium


### Forum Software

Maintainer:

### Tirex

Maintainer: nobody

### Overpass

Maintainer: Roland

### OWL

### JOSM


### osmc?

osmconvert, osmfilter

### imposm?
