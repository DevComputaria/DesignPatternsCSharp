`Singleton`__
=============

**THIS IS CONSIDERED TO BE AN ANTI-PATTERN! FOR BETTER TESTABILITY AND
MAINTAINABILITY USE DEPENDENCY INJECTION!**

Purpose
-------

To have only one instance of this object in the application that will
handle all calls.

Examples
--------

-  DB Connector
-  Logger
-  Lock file for the application (there is only one in the filesystem
   ...)
