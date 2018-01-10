# gradle-classloader

Apply Plugin in Apply From can't see outer Classpath because ClassLoader Scoping #4007

https://github.com/gradle/gradle/issues/4007

`gradlew --stacktrace --info --no-build-cache --refresh-dependencies --no-daemon --rerun-tasks tasks`

You should see publishListing* tasks appear from the 
class PlayPublisherPlugin implements Plugin<Project> 

plugin.xml is for cordova and not used by this example - just here for reference.
