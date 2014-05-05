hesaregatta
===========

Web Application for Helsinki Regatta Sailing Race Web Site

Admin java application can be downloaded at:
http://helsinkiregatta.appspot.com/helsinkiregatta-admin.zip

See Google App Engine documents at https://developers.google.com/appengine

See dependencies at pom.xml.

Compiling
---------
mvn install

Deployment
----------

Deploy to appengine
-------------------
mvn appengine:update

If update fails use 

mvn appengine:rollback
Commit to git
-------------

Change <version>3</version> 

in pom.xml

Deploy to Maven Central Repository
----------------------------------
not necessary
