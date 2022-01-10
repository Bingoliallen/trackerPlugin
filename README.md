# trackerPlugin

A android tracker plugin for fully buried points

# Usage 
plugins block:
```Java
plugins {
    id("io.github.bingoliallen.tracker-plugin") version "1.0.2.1"
}
```
Build script snippet for use in older Gradle versions or where dynamic configuration is required:

buildscript block:
```Java
apply plugin: "io.github.bingoliallen.tracker-plugin"

buildscript {

  repositories {
    maven {
      url "https://plugins.gradle.org/m2/"
    }
  }

  dependencies {
    classpath "io.github.bingoliallen.tracker-plugin:plugin:1.0.2.1"
  }

}

```

# Configuration
The following configuration block is required.

Add in gradle.properties
```Java

trackerPlugin=true

```
