# openfire jars

I couldn't find the openfire maven jars in any place but this repository:
http://repo.gltd.net/nexus/content/repositories/public/


It must be downloaded, build and added "by hand" to replace the legacy jtapi library

# JSR-43 Java(TM) Telephony API 1.4 Final Release 


[http://download.oracle.com/otndocs/jcp/jtapi-1.4-fr3-spec-oth-JSpec/](http://download.oracle.com/otndocs/jcp/jtapi-1.4-fr3-spec-oth-JSpec/)

# Installing into the maven local repository:

mvn install:install-file -Dfile=Gjtapi-1.8.jar -DgroupId -DartifactId=gjtapi -Dversion=1.8 -Dpackaging=jar 