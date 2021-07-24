# ubuntu-android-studio-proxy-fix
This is the file to fix you android studio when you use proxy and head back to non but the proxies remain 


#head to .gradle 

to the gradle.properties file open it and paste below code

```
# For more details on how to configure your build environment visit
# http://www.gradle.org/docs/current/userguide/build_environment.html
#
# Specifies the JVM arguments used for the daemon process.
# The setting is particularly useful for tweaking memory settings.
# Default value: -Xmx1024m -XX:MaxPermSize=256m
# org.gradle.jvmargs=-Xmx2048m -XX:MaxPermSize=512m -XX:+HeapDumpOnOutOfMemoryError -Dfile.encoding=UTF-8
#
# When configured, Gradle will run in incubating parallel mode.
# This option should only be used with decoupled projects. More details, visit
# http://www.gradle.org/docs/current/userguide/multi_project_builds.html#sec:decoupled_projects
# org.gradle.parallel=true
#Sat Jul 24 19:08:13 EAT 2021 </h1>
```

or just remove the lines of htt-proxy=_ _ _ _ _ _ _ _ 
