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
