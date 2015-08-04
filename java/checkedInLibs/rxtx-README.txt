Setting up RXTX
===============

The RXTX library is composed of a native and a Java library. The native part
is available as a package in Debian and can be installed on the Pi with
apt-get:

    sudo apt-get install librxtx-java

And normally this is all you have to do, as long as your Java library path
includes /usr/share/java/RXTXcomm.jar.

If you explicitly need the library, make sure you have the correct version
as the Java library needs to be the same version as the native library.
You can get the source from: http://rxtx.qbang.org/wiki/index.php/Download

