from https://www.youtube.com/watch?v=3Uhorh2o1dg&list=PLk7v1Z2rk4hjtIT9TCKIcl2YJYfDlZ_4v&index=3
https://github.com/probelalkhan/recyclerview-mvvm.git
https://github.com/heraldia/recyclerview-mvvm.git

# 2023_0507_1524
Caused by: org.gradle.api.InvalidUserCodeException: Querying the mapped value of map(java.io.File task ':app:compileDebugJavaWithJavac' property 'annotationProcessorSourcesDirectory' org.gradle.api.internal.file.DefaultFilePropertyFactory$ToFileTransformer@16930965) before task ':app:compileDebugJavaWithJavac' has completed is not supported

# Caused by: org.gradle.api.internal.artifacts.ivyservice.DefaultLenientConfiguration$ArtifactResolveException: Could not resolve all files for configuration ':app:debugCompileClasspath'.

## [Android studio 3.2.1 ArtifactResolveException: Could not resolve all artifacts for configuration ':classpath' - Stack Overflow](https://stackoverflow.com/questions/53932195/android-studio-3-2-1-artifactresolveexception-could-not-resolve-all-artifacts-f) { 


} #

# Could not determine the dependencies of task ':app:compileDebugJavaWithJavac'.
> Could not resolve all task dependencies for configuration ':app:debugCompileClasspath'.
   > Could not find org.kodein.di:kodein-di-generic-jvm:7.3.1.
     Required by:
         project :app

# 2023_0507_2051 
* What went wrong:
Execution failed for task ':app:compileDebugJavaWithJavac'.
> Failed to calculate the value of task ':app:compileDebugJavaWithJavac' property 'options.generatedSourceOutputDirectory'.
   > Querying the mapped value of map(java.io.File task ':app:compileDebugJavaWithJavac' property 'annotationProcessorSourcesDirectory' org.gradle.api.internal.file.DefaultFilePropertyFactory$ToFileTransformer@72cc1043) before task ':app:compileDebugJavaWithJavac' has completed is not supported
## [Querying the mapped value of map before task compileDebugJavaWithJavac has completed is not supported - Redino blog](http://redino.net/blog/2022/06/querying-the-mapped-value-of-map-before-task-compiledebugjavawithjavac-has-completed-is-not-supported/) { 

} #
## [我想调试下build.gradle | Gradle 调试-六虎](https://www.6hu.cc/archives/20250.html) { 

} #
   
./gradlew Assemble -Dorg.gradle.debug=true –no-daemon

# 2023_0507_2120
Caused by: org.gradle.api.internal.artifacts.ivyservice.DefaultLenientConfiguration$ArtifactResolveException: Could not resolve all files for configuration ':app:debugCompileClasspath'.
## [(293) Could not resolve all files for configuration ':app:debugRuntimeClasspath'. Error Fixed - YouTube](https://www.youtube.com/watch?v=NCzi0_I05yY) { 

} #

# 2023_0507_2155 
Cannot query the value of property 'namespace' because configuration of project ':app' has not completed yet.
