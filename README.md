This is a repo to use as a quickstart to start working with Spring Boot and deploying to the WildFly application server.  This uses the mvn build system and creates a .war file that can be deployed.  The code also contains a sample REST based service listening at /hello.

As an added bonus, this repo can also be deployed directly as a docker container using the WildFly S2I builder image on OpenShift 3 with the following command:

	oc new-app wildfly:10.0~https://github.com/gshipley/bootwildfly.git


What, you don't have OpenShift 3 yet? Fix that immediately: www.openshift.org/vm

Application is currently deployed here:

[http://spring-boot-on-wildfly-spring-boot-on-wildfly.44fs.preview.openshiftapps.com/index.html](Deployed application)








