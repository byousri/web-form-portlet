web-form-portlet
================

Contains an example how to extend Apps from Liferay Marketplace.

Pre-requisites
--------------

- Download Web Form CE version 2.0.1 (https://www.liferay.com/marketplace/-/mp/application/15195519)
- Unzip *Web Form CE.lpkg*
- Install WAR file in Maven local repository with the command above: 

mvn org.apache.maven.plugins:maven-install-plugin:2.5.1:install-file \
	-Dfile=web-form-portlet-6.2.0.2-ce-ga1-20140120092742162.war \
	-DgroupId=com.liferay.webform \
	-DartifactId=web-form-portlet \
	-Dversion=6.2.0-RC5 \
	-Dpackaging=war \
	-DlocalRepositoryPath=${user.home}/.m2/repository
