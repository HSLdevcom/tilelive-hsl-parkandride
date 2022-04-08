# tilelive-hsl-parkandride

This package contains tilelive-module which is used by [hsl-map-server](https://github.com/HSLdevcom/hsl-map-server). It downloads data from [LIIPI](https://p.hsl.fi/docs/index.html) and serves is as a tilelive vector tile interface.

If the connection to LIIPI cannot be created or LIIPI returns invalid data, dummy geojson is used to serve empty data instead of breaking the script.
