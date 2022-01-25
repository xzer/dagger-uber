# dagger-uber
There is no offical eclipse plugin for dagger, this uber jar for dagger can be used as annotation processor directly in project compiling configuration.

For different dagger version, just change the version in the pom accordinally. then run "mvn package", you will find the dagger-uber-jar-with-dependencies.jar under /target folder. 

Go https://immutables.github.io/apt.html to see how to configure annotation processor manually.
