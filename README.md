Project Overview

It’s a simple Java demo project created to test building with Maven.

The project only has one class: HelloWorld.java.

Its purpose is mainly educational — to show how to structure a Maven-based Java project, compile it, and run it.

📂 Structure

After fixing it to Maven standard layout, it looks like this:

**java-build/
 ├── pom.xml
 └── src/
      └── main/
           └── java/
                └── com/
                     └── example/
                          └── HelloWorld.java**
What pom.xml Does

Defines the project’s metadata (name, version, group ID).

Tells Maven it should package this as a JAR file.

Uses the exec-maven-plugin to allow running the app with mvn exec:java.
