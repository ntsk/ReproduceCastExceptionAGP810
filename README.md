```
class com.android.build.gradle.internal.dsl.AaptOptions$AgpDecorated_Decorated cannot be cast to class com.android.build.api.dsl.LibraryAndroidResources (com.android.build.gradle.internal.dsl.AaptOptions$AgpDecorated_Decorated and com.android.build.api.dsl.LibraryAndroidResources are in unnamed module of loader org.gradle.internal.classloader.VisitableURLClassLoader @62233f5d)
class com.android.build.gradle.internal.dsl.AaptOptions$AgpDecorated_Decorated cannot be cast to class com.android.build.api.dsl.LibraryAndroidResources (com.android.build.gradle.internal.dsl.AaptOptions$AgpDecorated_Decorated and com.android.build.api.dsl.LibraryAndroidResources are in unnamed module of loader org.gradle.internal.classloader.VisitableURLClassLoader @62233f5d)

Gradle's dependency cache may be corrupt (this sometimes occurs after a network connection timeout.)

Re-download dependencies and sync project (requires network)
The state of a Gradle build process (daemon) may be corrupt. Stopping all Gradle daemons may solve this problem.

Stop Gradle build processes (requires restart)
Your project may be using a third-party plugin which is not compatible with the other plugins in the project or the version of Gradle requested by the project.

In the case of corrupt Gradle processes, you can also try closing the IDE and then killing all Java processes.
```
