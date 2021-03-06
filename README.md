# Grails with react base application

### Prerequisites

### Install java

- [Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-ubuntu-16-04)
- [Windows](https://java.com/en/download/help/windows_manual_download.xml)

- `sudo apt-get update`
- `sudo apt-get install default-jre`
- `sudo apt-get install default-jdk`
- `sudo add-apt-repository ppa:webupd8team/java`
- `sudo apt-get update`
- `sudo apt-get install oracle-java8-installer`


### Install gradle

- [Ubuntu, Windows](https://gradle.org/install/)

- `$ sdk install gradle 4.9`
- `$ export PATH=$PATH:/opt/gradle/gradle-4.9/bin`


### Install grails

- [Ubuntu, Windows](http://grails.org/download.html)

- `$ curl -s "https://get.sdkman.io" | bash`
- `$ source "$HOME/.sdkman/bin/sdkman-init.sh"`
- `$ sdk install grails `
- `$ sdk install grails 3.2.4`
- `$ grails --version`


### Documentation

[Grails](http://guides.grails.org/creating-your-first-grails-app/guide/index.html)
[React](https://reactjs.org/docs/hello-world.html)

You can create your base application with the cli command from grails, you have the next profiles availables.

- `$ grails list-profiles`

| Available Profiles
--------------------
* angular - A profile for creating applications using AngularJS
* rest-api - Profile for REST API applications
* base - The base profile extended by other profiles
* angular2 - A profile for creating Grails applications with Angular 2
* plugin - Profile for plugins designed to work across all profiles
* profile - A profile for creating new Grails profiles
* react - A profile for creating Grails applications with a React frontend
* rest-api-plugin - Profile for REST API plugins
* web - Profile for Web applications
* web-plugin - Profile for Plugins designed for Web applications
* webpack - A profile for creating applications with node-based frontends using webpack

Create your application with profile
- `grails create-app myApp -profile rest-api`


### Start application

- You can start your client with the command `./gradlew client:start`
