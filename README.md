Old LightstreamerStore for Dojo
===============================

A Dojo Object Store implementation for integration between Lightstreamer HTML Client API 5 (part of Lightstreamer 4 Duomo) and Dojo Toolkit 1.7 or newer.

# LightstreamerStore
This package is designed to integrate the Lightstreamer JavaScript HTML Client API 5 with the dojo.store APIs. This object-based store is written so that the query method (to which you pass the name of the data adapter you want to use) returns a QueryResults object that is promise-based; all you need to do is attach a callback function to the "observe" method of the results to listen for any updates from the server. Each object returned by the server is passed to anything assigned to the "observe" function, which makes it simple to consume.

# Requisites
Note that the Lightstreamer HTML Client 5 library are not included as dependencies of the LightstreamerStore but are necessary to create an instance of LightstreamerStore. You should download the Lightstreamer libraries from the [Lightstreamer website](http://www.lightstreamer.com/download.htm) and include them in the application that is going to use the LightstreamerStore.

# License
The "New" BSD License
