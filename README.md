# MapDB API Plugin

This plugin provides a shared dependency on the [MapDB][upstream] library so that other plugins can co-operate when using this library.

See also this [plugin's wiki page][wiki]

# Environment

The following build environment is required to build this plugin

* `java-1.6` and `maven-3.0.5`

# Build

To build the plugin locally:

    mvn clean verify

# Release

To release the plugin:

    mvn release:prepare release:perform -B

# Test local instance

To test in a local Jenkins instance

    mvn hpi:run

  [upstream]: http://www.mapdb.org
  [wiki]: http://wiki.jenkins-ci.org/display/JENKINS/MapDB+API+Plugin