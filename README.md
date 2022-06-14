# JITSI MEET SDK 3.7.0 Maven binaries 

## TO USE
- unzip jitsi_maven.zip somewhere (to /tmp/jitsi_maven)
- edit app/build.gradle :

```
allprojects {
    repositories {
        maven { url "file:/tmp/repo" }
        google()
        jcenter()
    }
}
```

And your good to go ! 🚀
