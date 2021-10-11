A small example for replacing a library with a local jar.

## Instructions

1) Run gradle build in the source project to create a JAR file.
2) Copy the JAR file from `build/libs` to a local folder.
3) Replace the dependency in `build.gradle` (If it is transitive it will first need to be excluded from the parent).