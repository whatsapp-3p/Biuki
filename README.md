# Biuki
buildscript {
    repositories {
        // Add the following repositories:
        google()  // Google's Maven repository

        maven {
           url 'https://maven.fabric.io/public'
        }
    }

    dependencies {
        // ...

        // Check for v3.1.2 or higher
        classpath 'com.google.gms.google-services:4.2.0'

        // Add dependency
        classpath 'io.fabric.tools:gradle:1.29.0'
    }
}

allprojects {
    // ...

    repositories {
       // Check that you have the following line (if not, add it):
       google()  // Google's Maven repository
       // ...
    }
}
