# phonegap-media-test

Esto funcionó con unos cambios que están documentados en config.xml .

En general anda bien, pero de vez en cuando en cambio del porcentaje de batería muestra %undefined% .

Basado en http://codesnippets.altervista.org/examples/phonegap/demos/PUBLIC.Apps.html

---------------------------------------------------------------

A base test of phonegap's Media plugin

http://plugins.cordova.io/#/package/org.apache.cordova.battery-status

This code was made to work with the new W3C API.

It will detect power from laptops too. However, when runnig as an App you will likely get an `alert("Battery level is NOT supported.");`. This alert is intended only for laptops, not for the Phonegap API! This will be corrected in future versions.
