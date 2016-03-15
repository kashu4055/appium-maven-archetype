# appium-maven-archetype
The aim of this project is to provide a maven archetype for appium projets using the appium-handler available in https://github.com/agomezmoron/appium-handler 

## Prerequisites
1. [Appium installation and configuration](/Documentation/prerequisites/appiumInstall.md)
2. [Maven 3 configuration](/Documentation/prerequisites/maven3Installation.md)
3. [Java 8 installation](/Documentation/prerequisites/jave8Installation.md)
4. [Emulators](/Documentation/prerequisites/emulatorsInstallation.md)


## How to use the archetype
TODO

### Archetype structure
The archetype consist of several important parts, everything has been mounted on the structure of a Maven project.

###### In the root:

1. pom.xml: We have defined repositories for AppiumHandler, versions of plugins and technologies, properties of Phonegap and Appium, dependencies, profiles, and all the config for the Build phase.
2. downloadApp.sh: this script is executed before the project to download and install the app in the device/emulator.

###### In the src/test/resources:

1. Selectors: In this .properties we store the way to access to every element of every page. Using Xpath, ID, etc. That method modulates and encapsulates these variables, with the advantage that entails.
2. Suites: Here we can group sets of tests to run it together.
3. _test.properties & users.properties_: Here we store some common tests properties and the variables of the user's credentials.

###### In the src/test/java:

1. Page objects
2. Tests
3. utils

### Items selectors
TODO

### Native & Hybrid applications support
TODO

### Basic profiles
TODO
