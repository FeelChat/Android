# Gradle

## [Config Version](https://developer.android.google.cn/studio/build/gradle-plugin-3-0-0-migration)

### `gradle-wrapper.properties`

```
distributionUrl=...
```

## [Include Google's Maven repository](https://developer.android.com/studio/build/dependencies)

Edit `build.gradle`

```
allprojects {
    repositories {
        google()

        // If you're using a version of Gradle lower than 4.1, you must instead use:
        // maven {
        //     url 'https://maven.google.com'
        // }
        // An alternative URL is 'https://dl.google.com/dl/android/maven2/'
    }
}
```

## [Support Library Packages](https://developer.android.com/topic/libraries/support-library/packages)




